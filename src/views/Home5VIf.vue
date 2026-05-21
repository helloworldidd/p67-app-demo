
<template>

    <h2>5. v-if - Condicional</h2>

    <p class="verde" v-if="condicional">Esto es verdadero</p>
    <p class="rojo" v-else>Esto es falso</p>


</template>

<script setup>

const condicional = false;

</script>



<style lang="scss" scoped>
h2{
    margin: 20px 0;
    border-top: 1px solid #000;
}

.verde{
    color: green;
}
.rojo{
    color: red; 
}
</style>
