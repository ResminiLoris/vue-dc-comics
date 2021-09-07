<template>
    <div class="blue-banner">
      <div class="container row">
        <ul>
          <li>
            <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
          </li>
          <li>
            <img src="@/assets/img/buy-comics-merchandise.png" alt="">
            <span>DC merchandise</span>
          </li>
          <li>
            <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
            <span>subscription</span>
          </li>
          <li>
            <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
            <span>comic shop locator</span>
          </li>
          <li>
            <img class="reduce-image" src="@/assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC power visa</span>
          </li>
        </ul>
      </div>
    </div>
</template>

<script>
export default {
  name: 'BlueBanner',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .blue-banner{
    height: 180px;
    background-color: #0282F9;
  }
  .row{
    height: 100%;
    align-items: center;
  }

  img{
    height: 50px;
    vertical-align: middle;
    margin-right: 15px;
  }

  .reduce-image{
    height: 40px;
  }

  span{
    text-transform: uppercase;
    color: white;
    margin-right: 25px;
  }

  ul{
    margin: 0;
    padding: 0;
  }

  li{
    display: inline-block;
  }
</style>