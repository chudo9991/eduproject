<script setup>
  import BlueButton from './BlueButton.vue'
</script>

<template>
  <div class="whiteone__wrapper">
    <div class="whiteone__first">
      <div class="whiteone__first__text">
        <p class="whiteone__text__header">Find Your Course That Makes Bright Future</p>
        <p class="whiteone__text__big">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas voluptates ducimus voluptatem magnam, laborum nemo dolorum quo aspernatur beatae aliquid, quidem sit similique qui nihil praesentium explicabo provident ipsum ratione!</p>
        <p class="whiteone__text__small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque nobis numquam cum repudiandae magnam rerum veniam aspernatur iure praesentium totam culpa iste, adipisci facere, similique perspiciatis placeat architecto vel sequi!</p>
        <BlueButton msg1="Learn More" />
      </div>
      <div class="whiteone__first__picture"></div>
    </div>
  </div>
</template>

<style scoped>
  .whiteone__wrapper {
    margin: 0;
    padding: 232px 144px 128px 144px;
    height: 1300px;
    /* background: red; */
  }

  .whiteone__first {
    height: 433px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .whiteone__first__text {
    text-align: left;
    width: 519px;
    font-family: DM Sans;
    font-style: normal;
    font-weight: bold;
  }

  .whiteone__text__header {
    font-size: 48px;
    line-height: 62px;
    color: #222222;
  }
  .whiteone__text__big {
    font-size: 20px;
    line-height: 28px;
    color: #333333;
  }
  .whiteone__text__small {
    font-size: 16px;
    line-height: 155%;
    color: #555555;
  }

  .whiteone__first__picture {
    width: 595px;
    height: 100%;
    background-image: url('../assets/first_picture.png');
  }

</style>
