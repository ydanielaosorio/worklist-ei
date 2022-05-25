<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <WorkList msg="WorkList"/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import WorkList from './components/WorkList.vue'

export default {
  name: 'App',
  components: {
    WorkList
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
