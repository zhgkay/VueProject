<template>
  <div id="app">
    <router-view/>
    <Footer_gzh></Footer_gzh>
  </div>
</template>

<script>
  import './screen/zsy';
  import Footer_gzh from "./components/Footer_gzh";
export default {
  name: 'App',
  components: {Footer_gzh}
}
</script>

<style>
html,body{
  font-size: 20px;
  width: 100%;
  height: 100%;
}
</style>
