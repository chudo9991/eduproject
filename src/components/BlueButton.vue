<script setup>
import { ref } from 'vue'

defineProps({
  msg1: String
})

</script>
  
<template>
  <button class="bluebutton">{{ msg1 }}</button>
</template>

<style scoped>
  .bluebutton {
        font-family: DM Sans;
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 24px;

        padding: 12px 24px;
        background-color: #086CF9;
        color: #fff;
        border-radius: 4px;
  }
</style>
