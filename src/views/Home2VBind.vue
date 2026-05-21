<template>
    <h2>2. v-bind</h2>
    <img v-bind:src="photo1">
    <img :src="photo2">

  
</template>

<script setup>
 const photo1 =  "https://picsum.photos/100";
 const photo2 = "https://picsum.photos/120";

</script>

<style lang="scss" scoped>
h2{
    margin: 20px 0;
    border-top: 1px solid #000;
}
</style>