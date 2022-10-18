<template>
    <img alt="aablar logo" src="./assets/logo.png" width="400">
    <p>The first global chatbot search engine...</p>
    <MainSearch />

    <!--<HelloWorld msg="Welcome to Vue..."/>-->
</template>

<script>
    import HelloWorld from './components/HelloWorld.vue'
    import MainSearch from './components/MainSearch.vue'

export default {
  name: 'App',
  components: {
      HelloWorld,
      MainSearch
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
