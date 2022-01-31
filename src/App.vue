<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Preferences from './components/Preferences.vue'
import WhiteOne from './components/WhiteOne.vue'
</script>

<template>
  <Header msg1="zzz"/> 
  <Hero />
  <Preferences/>
  <WhiteOne />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans&display=swap');

html, body {
  margin: 0;
  padding: 0;
}
.test {
  height: 400px;
  background: red;
}

#app {
  font-family: 'DM Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
