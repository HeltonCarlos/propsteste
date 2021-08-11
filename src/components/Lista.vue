<template>
  <div>
  <div  class="fundo">
    <CardLista :parte01="parte01"/>
  </div>
  </div>
</template>

<script>
import CardLista from './CardLista.vue'
export default {
  props:['parte01','parte02'],
  components: { CardLista },
  data(){
      return{
      }
  }
}
</script>
<style scoped>

.fundo{background-color: rgba(8, 210, 224,0.5);}
</style>