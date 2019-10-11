<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  import './screen/zsy';
  export default {
    name: 'App',
    components: {}
  }
</script>

<style>
  #app{
    background: #f5f5f5;
  }
  *{
    padding: 0;
    margin: 0;
    list-style: none;
    text-decoration: none;
  }
  html,body{
    font-size: 20px;
    width: 100%;
    height: 100%;
  }
</style>
