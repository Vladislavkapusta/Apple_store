<template>
  <div id="app">
    <div class="container">
      <HeaderComponent></HeaderComponent>
      <ScrollerComponent></ScrollerComponent>
      <InfoComponent></InfoComponent>
      <PlusesComponent></PlusesComponent>
      <SubscriptionComponent></SubscriptionComponent>
      <FooterComponent></FooterComponent>
    </div>
  </div>
</template>



<script setup>
import PlusesComponent from './components/PlusesComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import InfoComponent from './components/InfoComponent.vue';
import ScrollerComponent from './components/ScrollerComponent.vue';
import SubscriptionComponent from './components/SubscriptionComponent.vue';
import FooterComponent from './components/FooterComponent.vue'

</script>

<style>

  body{
    /* overflow-x: hidden; */
  }

  *{
    margin: 0;
    font-family: 'SF Pro Display', sans-serif;
    
  }

  .container{
    display: flex;
    flex-direction: column;
    /* margin-left: auto;
    margin-right: auto; */
  }
 /* @media screen and (width > 1440px){
  .container{
    width: 1200px;
  }
 } */
</style>

