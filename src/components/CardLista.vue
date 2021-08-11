<template>
   <div>
     <div v-if="modelos==parte01">
        <p>PEGOU 2</p>
        <h2>valores1</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
     <div v-if="modelos==parte02">
        <p>PEGOU 2</p>
        <h2>valores2</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
   </div>
</template>

<script>
export default {
    props:['modelos'],
    data () {
        return {}
    }
}
</script>
<style scoped>
img{width: 100px;}
</style>