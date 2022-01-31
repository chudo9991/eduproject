<script setup>

</script>

<template>
  <div class="preferences__wrapper">

    <div class="item">
      <svg width="70" height="70">
          <use xlink:href="../assets/sprite.svg#lecture"/>
        </svg>
        <div class="item__text">
          <p class="item__big">1400+</p>
          <p class="item__small">Online Courses</p>
        </div>
    </div>

    <div class="item">
      <svg width="70" height="70">
          <use xlink:href="../assets/sprite.svg#instructor"/>
        </svg>
        <div class="item__text">
          <p class="item__big">1100+</p>
          <p class="item__small">Expert Instructors</p>
        </div>
    </div>

    <div class="item">
      <svg width="70" height="70">
          <use xlink:href="../assets/sprite.svg#success"/>
        </svg>
        <div class="item__text">
          <p class="item__big">800+</p>
          <p class="item__small">Success Stories</p>
        </div>
    </div>

  </div>
</template>

<style scoped>
  .preferences__wrapper {

    margin: 0;
    padding: 0;

    position: absolute;
    top: calc(120px + 739px - 96px);
    left: calc( (100% - 1138px) / 2);
    z-index: 2;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 1138px;
    height: 192px;

    font-family: DM Sans;
    font-style: normal;
    font-weight: normal;

    box-shadow: 0px 11px 35px rgba(0, 0, 0, 0.08);
    border-radius: 4px;
    background: #FFFFFF;

    /* margin: 0 auto; */
  }
  .item {
    display: flex;
    align-items: center;
    font-family: DM Sans;
    font-style: normal;
    font-weight: bold;
  }

  .item__text {
    margin-left: 24px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: flex-start;
    
  }

  .item__big {
    margin: 0;
    padding: 0;
    font-size: 36px;
    line-height: 47px;    
    color: #222222;
  }

  .item__small {
    font-size: 16px;
    line-height: 155%;
    color: #086CF9;
    margin: 0;
    padding: 0;
  }
</style>
