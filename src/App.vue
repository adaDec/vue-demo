<template>
  <div id="app">
    <Nav/>
    <Header />
    <Banner />
  </div>
</template>
<script>
//导入组件
import Header from './components/header.vue'
import Nav from './components/nav.vue'
import Banner from './components/banner.vue'

export default {
  name: 'App',
  components: {
    Header,
    Nav,
    Banner
  }
}
</script>
<!-- 样式代码 -->
<style>
*{
  margin: 0;
  padding: 0;
}
</style>
