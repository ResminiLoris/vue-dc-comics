<template>
  <div id="app">
    <Header/>
    <Jumbo/>
    <Footer/>
    <Banner/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Jumbo from './components/Jumbo.vue';
import Footer from './components/Footer.vue';
import Banner from './components/Banner.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Footer,
    Banner,


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
    &:hover{
      color:#0C7CEC;
    }
    
  }
  //utils
  .blue{
    color: #0C7CEC;
  }
  //reset lists
  ul{
    list-style-type: none;
  }
  .container{
    max-width: 1200px;
    margin: 0 auto;
  }
}
</style>
