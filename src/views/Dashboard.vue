<template>
    <div class="dark">
        <CardLista :valor01="valor01" />
    </div>
</template>

<script>
import CardLista from '@/components/CardLista.vue';
export default {
  name: 'Dashboard',
  components: {
    CardLista
  },
  data(){
    return {
      valor01:true,
    }
  }
}
</script>

<style scoped>
.dark{background-color: #000000;width: 250px;
height: 250px;border-radius:8px ;margin: 20px;}
</style>
