<script setup>
  import BlueButton from './BlueButton.vue'
</script>

<template>
  <div class="hero__wrapper">
    <h1>Self-Placed Learning Courses Online</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed amet architecto iure praesentium qui facere repellendus quia minima tempora, provident tenetur voluptates libero quisquam rem ipsa unde! Voluptas, excepturi non!</p>
    <BlueButton msg1="Start a cources" />
  </div>
</template>

<style scoped>
  .hero__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: relative;
    height: 739px;
    color: #fff;
    padding: 0 235px;    

    font-family: DM Sans;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 155%;
    
  }
  .hero__wrapper::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('../assets/hero.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    z-index: -1;
    filter: brightness(0.54)
  }

  .hero__wrapper > h1 {
    font-size: 56px;
    line-height: 73px;
  }


</style>
