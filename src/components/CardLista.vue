<template>
   <div>
     <div v-if="modelos==='valor01'">
        <p>PEGOU 1</p>
        <h2>valores1</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
     <div v-if="modelos==='valor02'">
        <p>PEGOU 2</p>
        <h2>valores2</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
   </div>
</template>

<script>
export default {
    props:['modelos'],
}
</script>
<style scoped>
img{width: 100px;}
</style>