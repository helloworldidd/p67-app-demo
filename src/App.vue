<script setup>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';


</script>

<template>
  <div class="page">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
    
</template>


<style scoped>

.page{
  border: 1px solid #000;
  background-color: rgb(140, 192, 213);
  padding: 10px;
}


</style>
