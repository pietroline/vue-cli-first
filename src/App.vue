<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle></MyTitle>
    <MainJumbotron></MainJumbotron>
  </div>
</template>

<script>

  import MyTitle from './components/MyTitle.vue'
  import MainJumbotron from './components/MainJumbotron.vue'

  export default {
    name: 'App',
    components: {
      MyTitle,
      MainJumbotron,
    }
  }
  
</script>

<style lang="scss">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
