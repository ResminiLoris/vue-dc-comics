<template>
    <div class="footer">
        <section class="container">
            <div class="row main">
                <div class="col-6">
                    <div id="links" class="row">
                        <div class="col-4">
                            <ul>
                                <li class="list-title">DC comics</li>
                                <li> <a href="#"> characters</a></li>
                                <li> <a href="#"> comics</a></li>
                                <li> <a href="#"> movies</a></li>
                                <li> <a href="#"> tv</a></li>
                                <li> <a href="#"> games</a></li>
                                <li> <a href="#"> videos</a></li>
                                <li> <a href="#"> news</a></li>
                            </ul>
                            <ul>
                                <li class="list-title"> Shop</li>
                                <li> <a href="#"> Shop DC</a></li>
                                <li> <a href="#"> Shop DC collectibles</a></li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li class="list-title"> DC</li>
                                <li> <a href="#"> DC comics</a></li>
                                <li> <a href="#"> characters</a></li>
                                <li> <a href="#"> comics</a></li>
                                <li> <a href="#"> movies</a></li>
                                <li> <a href="#"> tv</a></li>
                                <li> <a href="#"> games</a></li>
                                <li> <a href="#"> videos</a></li>
                                <li> <a href="#"> news</a></li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <ul>
                                <li class="list-title">Sites</li>
                                <li> <a href="#"> DC</a></li>
                                <li> <a href="#"> MAD Kids</a></li>
                                <li> <a href="#"> DC Kids</a></li>
                                <li> <a href="#"> DC Universe</a></li>
                                <li> <a href="#"> DC Power Visa</a></li>
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
        font-weight: bolder;
        text-transform: uppercase;
        color: lightgray;
    }

    #links{
        li{
            padding-bottom: 5px;
            a{
                color: gray;
                &:hover{
                    border-bottom: 2px solid #0C7CEC;
                }
            }
        }
    }
</style>
