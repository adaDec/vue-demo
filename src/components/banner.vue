<template>
  <div class="banner-box">
    <img :src="imgUrl" width="100%" />
  </div>
</template>

<script>
export default {
  name: 'Banner',
  props: {
    msg: String
  },
  data() {
    return {
      imgUrl: ""
    }
  },
  created() {
    let urlTemp = "assets/banner.png";
    this.imgUrl = require("@/" + urlTemp)
  }
}
</script>

<style scoped>
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
</style>
