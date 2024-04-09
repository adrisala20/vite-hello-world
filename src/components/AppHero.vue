<template>
    <div>
        <img :src="img" alt="jumbo">
    </div>
</template>

<script>
    export default {
        name:'AppHero',
        data(){
            return{
                img:'/img/jumbo.png'
            }
        }
    }
</script>

<style scoped>

</style>