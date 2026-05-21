<template>

    <header class="header
            animate__animated
            animate__fadeInDown
            animate__delay-2s
            ">
        <h1 class="
            title
            
        ">Titulo de la página</h1>
        <NavBar />
    </header>
    
</template>



<script setup>
import NavBar from './NavBar.vue';


</script>




<style lang="scss" scoped>


.header{
    border: 1px solid #000;
    background-color: rgb(84, 124, 139);
    padding: 10px;
}

.title{
    color: #fff;
    font-size: 20px;
}

</style>