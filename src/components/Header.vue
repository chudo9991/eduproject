<script setup>
import { ref } from 'vue'
import BlueButton from './BlueButton.vue'

defineProps({
  msg1: String
})

</script>

<template>
  <div class="header__wrapper">
    <span class="Education">Education</span>
    <nav>
      <li class="header__list-item">
        Home
        <svg width="10" height="5">
          <use xlink:href='../assets/sprite.svg#chevron'/>
        </svg>
      </li>
      <li class="header__list-item">
        Courses
        <svg width="10" height="5">
          <use xlink:href='../assets/sprite.svg#chevron'/>
        </svg>
        </li>
      <li class="header__list-item">
        Page
        <svg width="10" height="5">
          <use xlink:href='../assets/sprite.svg#chevron'/>
        </svg>
      </li>
      <li class="header__list-item">
        Blog
        <svg width="10" height="5">
          <use xlink:href='../assets/sprite.svg#chevron'/>
        </svg>
      </li>
      <li class="header__list-item">
        Contact
        <svg width="10" height="5">
          <use xlink:href='../assets/sprite.svg#chevron'/>
        </svg>
      </li>
    </nav>
      <span class="signin">Signin</span>
      <BlueButton msg1="Sign Up" />
  </div>
</template>

<style scoped>
  .header__wrapper {
    display: flex;
    height: 120px;
    justify-content: space-between;
    align-items: center;
    border: 1px solid red;;
    margin: 0;
    padding-left: 144px;
    padding-right: 144px;
  }

  .Education {
    font-family: DM Sans;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 31px;

    color: #222222;
  }
  
  nav {
    display: flex;
    width: 60%;
    justify-content: space-evenly;
    align-items: center;
  }

  .header__list-item, .signin {
    list-style: none;
    font-family: DM Sans;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 155%;
  }

  .header__list-item:first-child {
    color: #086CF9;
  }
  .signup {
    padding: 12px 24px;
    background-color: #086CF9;
    color: #fff;
    border-radius: 4px;
  }
</style>
