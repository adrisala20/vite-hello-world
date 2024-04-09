<template>
    <div>
        <img :src="img" alt="hero">
    </div>
</template>

<script>
    export default {
        name:'AppHero',
        data(){
            return{
                img:'/img/hero.jpg'
            }
        }
    }
</script>

<style scoped>
img{
   width: 100%;
   height: 100vh;
   filter: blur(2px);
   background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

</style>