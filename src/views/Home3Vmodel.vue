<template>

    <h2>3. v-model - two way binding</h2>

    <input type="text" v-model="message">
    <p>{{ message }}</p>


</template>

<script setup>

import { ref } from 'vue';

const message = ref("")

</script>



<style lang="scss" scoped>
h2{
    margin: 20px 0;
    border-top: 1px solid #000;
}
</style>
