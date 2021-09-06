<template>
  <div id="app">
    <Header/>
    <Jumbo/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
  }
}
</script>

<style lang="scss">
#app {
  //reset
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  //reset links
  a{
    text-decoration: none;
    color: black;
    
  }
  .container{
    max-width: 1200px;
    margin: 0 auto;
  }
}
</style>
