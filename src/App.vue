<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <CommonPage/>
</template>

<script>
import CommonPage from './components/CommonPage.vue'

export default {
  name: 'App',
  components: {
    CommonPage
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
  margin-top: 60px;
}
</style>
