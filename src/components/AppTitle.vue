<template>
    <h1>
        {{ title }}
    </h1>
</template>

<script>
    export default {
        name:'AppTitle',
        data(){
            return{
                title: 'La mia prima app con Vite!'
            }
        }     
    }
</script>
<style scoped>
h1{
  background-color: rgb(0,0,0); 
  background-color: rgba(0,0,0, 0.4);
  color: white;
  font-weight: bold;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
}
</style>