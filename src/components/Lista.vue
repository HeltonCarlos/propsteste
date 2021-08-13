<template>
  <div>
  <div class="fundo">
    <CardLista :modelos="Valor01"/>
    <CardLista :modelos="Valor02"/>
  </div>
  </div>
</template>

<script>
import CardLista from './CardLista.vue'
export default {
  components: { CardLista },
}
</script>
<style scoped>
.fundo{background-color: rgba(8, 210, 224,0.5);}
</style>