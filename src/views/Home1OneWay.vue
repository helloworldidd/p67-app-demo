<template>
    <h2>1. One Way Binding</h2>
    <p>{{ user.name }} - {{ user.age }}</p>
</template>




<script setup>
const user = {
    name: "John Doe",
    age: 30
}
    const message = "One Way Binding ⭐"
</script>






<style lang="scss" scoped>
h2{
    margin: 20px 0;
    border-top: 1px solid #000;
}
</style>