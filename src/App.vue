<template>
  <div id="app">
    <baseVue/>
  </div>
</template>

<script>
import baseVue from './components/baseVue.vue'
export default {
  name: 'App',
  components: {
    baseVue
  }
}
</script>

<style>
body{
    font-family: Ubuntu;
    color: #555;
}
</style>
