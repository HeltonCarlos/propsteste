<template>
   <div>
     <div class="green" v-show="valor01">
        <p>PEGOU 1</p>
        <h2>valores1</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
     <div class="blue" v-show="valor02">
        <p>PEGOU 2</p>
        <h2>valores2</h2>
        <img src="@/assets/logo.png" alt="vue"/>
    </div>
   </div>
</template>

<script>
export default {
 props:['valor01','valor02']
}
</script>
<style scoped>
img{width: 100px;}
.blue{background-color: #03c4ff;color: rgb(71, 71, 71);padding-top:"20px"}
.green{background-color: #03ff42;color: rgb(71, 71, 71);margin-top:"20px"}
</style>