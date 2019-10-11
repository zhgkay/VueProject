<template>
  <div id="app">
    <E_me_zhm></E_me_zhm>
    <router-view/>
  </div>
</template>

<script>
import E_me_zhm from "./components/E_me_zhm";
export default {
  name: 'App',
  components: {E_me_zhm}
}
</script>

<style>
#app {

}
</style>
