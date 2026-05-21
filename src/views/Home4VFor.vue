<template>

    <h2>4. v-for - Ciclo</h2>
    <ul>
        <li v-for="juguete in juguetes" :key="juguete">{{juguete}}</li>
    </ul>



</template>

<script setup>

const juguetes = [
    "pelota",
    "muñeca",
    "legos",
    "oso",
    "crayones"
]

</script>



<style lang="scss" scoped>
h2{
    margin: 20px 0;
    border-top: 1px solid #000;
}
</style>
