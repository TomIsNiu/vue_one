<template>
  <div id="app">
    <MyHeader></MyHeader>
    <router-view/>
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader";
export default {
  name: 'App',
  components: {MyHeader}
}
</script>

<style>
  html,body{
    width: 100%;
    height: 100%;
  }
#app {
  width: 100%;
  height: 100%;
}
</style>
