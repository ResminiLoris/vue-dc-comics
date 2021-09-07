<template>
  <div id="app">
    <Header/>
    <Jumbo/>
    <BlueBanner/>
    <Footer/>
    <Banner/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Jumbo from './components/Jumbo.vue';
import Footer from './components/Footer.vue';
import Banner from './components/Banner.vue';
import BlueBanner from './components/BlueBanner.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Footer,
    Banner,
    BlueBanner,


  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,700;1,900&display=swap');

body{
  margin: 0;
  font-family: 'Roboto', sans-serif;
}
#app {
  //reset links
  a{
    text-decoration: none;
    color: black;
    &:hover{
      color:#0C7CEC;
      border-bottom: 5px solid #0C7CEC;
    }
    
  }
  //utils
  .blue{
    color: #0C7CEC;
  }
  .row{
    display: flex;
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
