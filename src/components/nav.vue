<template>
  <div class="maxtop-box">
    <div class="left-box">欢迎您访问xxx集团网站</div>
    <div class="right-box-eve">
      <a class="right-eve-box">碧水源</a>
      <a class="right-eve-box">7.22</a>
      <a class="right-eve-box-w">+0.70%</a>
      <a class="right-eve-box-e ">碧水集团子公司</a>
      <a class="right-eve-box-e">English</a>
      <a class="right-box">集团微信矩阵</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.maxtop-box {
  display: flex;
  justify-content: space-between;
  background-color: black;
  font-family: "微软雅黑";
  font-size: 14px;
  color: #fff;
  line-height: 40px;
}

.left-box {
  padding-left: 150px;
  padding-right: 150px;
}

.right-box {
  padding-right: 150px;
  padding-left: 7px;
}

.right-eve-box {
  padding: 0 7px;
}

.right-eve-box-w {
  padding: 0 7px;
  color: red;
}

.right-eve-box-e {
  padding: 0 7px;
  border-right: blue;
}

</style>
