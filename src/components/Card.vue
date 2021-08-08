<template>
  <div class="CardLista">
  <p class="texto">texto-cima</p>
  <div>
    <Lista :parte01="parte01"/>
    <Lista :parte02="parte02"/>
  </div>
  </div>
</template>

<script>
import Lista from './Lista.vue'
export default {
   props:['parte01','parte02'],
  components: { Lista },
  data(){
      return{
      }
  }
}
</script>
<style scoped>
.CardLista{background-color: rgb(41, 40, 40);padding: 5px 20px 20px 20px;
width: 350px;height: 220px;border-radius: 5px;}
.texto{color:#fff}
</style>