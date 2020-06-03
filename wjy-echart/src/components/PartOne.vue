<template>
  <div class="part-one">
    <img class="part-one-image" :src="headImage" alt="头像">
    <p>姓&emsp;&emsp;名：王佳苑</p>
    <p>学&emsp;&emsp;历：高中</p>
    <p>工作年限：1 年</p>
    <p>年&emsp;&emsp;龄：21</p>
    <p>联系电话：15379687810</p>
    <p>电子邮箱：2684842185@qq.com</p>
    <p>掘&emsp;&emsp;金：<a href="https://juejin.im/post/5ecfc162f265da76d85d0a8c" target="_blank">wangjiayuan</a></p>
    <p>GitHub：<a href="https://github.com/wangjiayuans/echarts_demo.git" target="_blank">wangjiayuans</a></p>
  </div>
</template>

<script>
export default {
  name: "partOne",
  data() {
    return {
      headImage: require('../assets/img/head_image.png')
    }
  }
};
</script>

<style scoped>
a {
  color: deepskyblue;
}
a:hover {
  color: rgb(118, 190, 248);
}
p {
  line-height: 30px;
}
.part-one {
  width: 100%;
  height: 500px;
  border: 40px solid transparent;
  border-image: url("~@/./assets/img/border_image.png") 30 30 stretch;
  background: #18202d;
  padding-left: 10px;
}
.part-one-image {
  width: 150px;
  height: 150px;
}
</style>