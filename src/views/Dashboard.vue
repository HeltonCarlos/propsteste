<template>
    <div>
        <Card :parte01="parte01=true"/>
        <Card :parte02="parte02=true"/>
    </div>
</template>

<script>
import Card from '@/components/Card.vue'

export default {
  name: 'App',
  components: {
    Card
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
