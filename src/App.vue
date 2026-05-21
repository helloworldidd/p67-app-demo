<script setup>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
import Home1OneWay from './views/Home1OneWay.vue';
import Home2VBind from './views/Home2VBind.vue';
import Home3Vmodel from './views/Home3Vmodel.vue';
import Home4VFor from './views/Home4VFor.vue';
import Home5VIf from './views/Home5VIf.vue';


</script>

<template>
  <div class="page">
    <!-- <HeaderComponent />
    <MainComponent />
    <FooterComponent /> -->

    <Home1OneWay />
    <Home2VBind />
    <Home3Vmodel />
    <Home4VFor />
    <Home5VIf />
  </div>
    
</template>


<style scoped>

.page{
  border: 1px solid #000;
  background-color: rgb(140, 192, 213);
  padding: 10px;
}


</style>
