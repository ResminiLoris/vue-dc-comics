<template>
    <div class="footer">
        <section class="container">
            <div class="row main">
                <div class="col-6">
                    <div class="row">
                        <div class="col-4">
                            <ul>
                                <li class="list-title">DC comics</li>
                                <li>characters</li>
                                <li>comics</li>
                                <li>movies</li>
                                <li>tv</li>
                                <li>games</li>
                                <li>videos</li>
                                <li>news</li>
                            </ul>
                            <ul>
                                <li class="list-title">Shop</li>
                                <li>Shop DC</li>
                                <li>Shop DC collectibles</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li class="list-title">DC</li>
                                <li>DC comics</li>
                                <li>characters</li>
                                <li>comics</li>
                                <li>movies</li>
                                <li>tv</li>
                                <li>games</li>
                                <li>videos</li>
                                <li>news</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li class="list-title">Sites</li>
                                <li>DC</li>
                                <li>MAD Kids</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <figure>
                        <img src="@/assets/img/dc-logo-bg.png" alt="">
                    </figure>
                </div>
            </div>
        </section>
    </div> 
</template>

<script>
export default {
  name: 'Footer',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .footer{
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        color: gray;
    }
    .row{
        display: flex;

    }
    .row.main{
        align-items: center;
    }
    .col-6{
        width: calc(100% / 2);
    }
    .col-4{
        width: calc(100% / 3);
    }
    .list-title{
        padding-bottom: 10px;
        font-weight: bold;
        text-transform: uppercase;
        color: lightgray;
    }
    li{
        padding-bottom: 5px;
    }
</style>
