<template>
  <div class="top-box">
    <div class="imgtop-box">
      <img :src="imgUrl" />
    </div>
    <div class="topbanner-box">
      <ul>
        <a class="yemei-box">首页</a>
        <a class="yemei-box">关于碧水源</a>
        <a class="yemei-box">技术中心</a>
        <a class="yemei-box">产品与技术</a>
        <a class="yemei-box">业务领域</a>
        <a class="yemei-box">公司业绩</a>
        <a class="yemei-box">投资者关系</a>
        <a class="yemei-box">加入碧水源</a>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  },
  data() {
    return {
      imgUrl:" "
    }
  },
  created() {
    let urlTemp = "assets/logotop.png";
    this.imgUrl = require("@/" + urlTemp)
  }
}
</script>

<style scoped>
.top-box {
  display: flex;
  justify-content: space-between;
}

.imgtop-box {
  margin-top: 15px;
  margin-bottom: 10px;
  padding-left: 150px;
  padding-right: 150px;
}

.topbanner-box {
  padding: 0 8px;
  font-size: 16px;
  color: #333;
  line-height: 96px;
  display: block;
  border-bottom: 4px solid #fff;
  cursor: hand;
  margin-right: 150px;
}

.yemei-box {
  padding: 0 17px;
}


</style>
