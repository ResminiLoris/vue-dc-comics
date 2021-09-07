<template>
    <div class="banner">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <span class="btn">Sign Up Now!</span>
                </div>
                <div class="col-6 row icon-row">
                    <div class="col-3">
                        <span class="blue follow">FOLLOW US</span>
                    </div>
                    <img src="@/assets/img/footer-facebook.png" alt="">
                    <img src="@/assets/img/footer-periscope.png" alt="">
                    <img src="@/assets/img/footer-pinterest.png" alt="">
                    <img src="@/assets/img/footer-twitter.png" alt="">
                    <img src="@/assets/img/footer-youtube.png" alt="">
                    
                </div>
            </div>
        </div>  
    </div>
</template>

<script>
export default {
  name: 'Banner',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .banner{
        height: 150px;
        line-height: 150px;
        background-color: #303030;
    }
    .btn{
        padding: 20px 30px;
        border: 2px solid #0C7CEC;
        color: white;
        text-transform: uppercase;
        font-weight: bold;
    }
    .col-6{
        width: calc(100% / 2);
    }
    .col-3{
        width: calc(100% / 4);
    }
    .icon-row{
        justify-content: space-between;
        align-items: center;
    }
    .follow{
        font-size: 20px;
        font-weight: bolder;
    }
</style>
