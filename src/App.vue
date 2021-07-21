<template>
  <div id="app">
    <CustomsButton/>
  </div>
</template>

<script>
import  CustomsButton from './components/CustomsButton.vue'

export default {
  name: 'App',
  components: {
    CustomsButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
