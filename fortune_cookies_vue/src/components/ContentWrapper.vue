
<script setup>
import MainScene from './MainScene.vue'
import ButtonsComponent from './ButtonsComponent.vue'
</script>

<template>
  <div class="content-wrapper">
    <MainScene />
    <ButtonsComponent />
  </div>

</template>
  
  <style scoped>
   .content-wrapper {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* background-color: var(--main-wrapper-color);
    border: 1px solid #ADA17B;
    border-radius: 30px; */
    min-height: 900px;
    min-width: 900px;
    margin: auto;
    /* padding: 2rem;
    font-weight: normal; */
  } 

  </style>
  