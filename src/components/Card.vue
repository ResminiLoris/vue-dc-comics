<template>
    <div class="card">
        <div class="comic-cover">
            <img :src="comic.thumb" alt="">
        </div>
        <h3>{{comic.series}}</h3>
    </div>
</template>

<script>
export default {
  name: 'Card',
  props:['comic'],
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .card{
        flex-basis: calc(100% / 6);
    }
    .comic-cover{
        height: 50%;
        overflow: hidden;
    }
    
</style>
