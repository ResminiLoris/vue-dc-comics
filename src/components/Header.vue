<template>
  <div class="Header">
    <header class="container">
      <div class="row">
        <div class="col">
          <figure>
            <img src="@/assets/img/dc-logo.png" alt="">
          </figure>
        </div>
        <div class="col">
          <figure>
            <nav>
              <ul>
                <li> <a href="#">characters</a></li>
                <li> <a href="#">comics</a></li>
                <li> <a href="#">movies</a></li>
                <li> <a href="#">tv</a></li>
                <li> <a href="#">games</a></li>
                <li> <a href="#">collectibles</a></li>
                <li> <a href="#">videos</a></li>
                <li> <a href="#">fans</a></li>
                <li> <a href="#">news</a></li>
                <li> <a href="#">shop</a></li>
              </ul>
            </nav>
          </figure>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  figure{
    display: inline-block;
  }

  ul li{
    display: inline-block;
    font-size: 20px;
  }

  ul li a{
    padding-left: 30px;
    padding-bottom: 80px;
  }

  .row{
    display: flex;
  }
  
</style>
