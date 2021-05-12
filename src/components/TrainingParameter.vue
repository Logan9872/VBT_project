<template>
  <div class="contrainer">
    <div class="tra-parameter">
      <div class="sets"></div>
      <div class="reps"></div>
      <div class="body-weight"></div>
      <div class="parameter-setting">
        <div class="target-setting"></div>
        <div class="player-setting"></div>
        <div class="group-setting"></div>
        <div class="max-setting"></div>
        <div class="data-display"></div>
      </div>
      <div class="load-weight"></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "tra-parameter",
};
</script>
<style lang="scss">
@import "./../assets/scss/confing.scss";
@import "./../assets/scss/base.scss";
.contrainer {
  .tra-parameter {
    position: absolute;
    left: 200px;
    top: 60px;
    width: 625px;
    height: 340px;
    background-color: $colorJ;

    .sets {
      position: absolute;
      top: 24px;
      left: 48px;
      width: 140px;
      height: 140px;
      background-color: $colorK;
      border-radius: 140px;
    }
    .reps {
      position: absolute;
      top: 24px;
      left: 430px;
      width: 140px;
      height: 140px;
      background-color: $colorK;
      border-radius: 140px;
    }
    .body-weight {
      position: absolute;
      top: 174px;
      left: 48px;
      width: 140px;
      height: 140px;
      background-color: $colorK;
      border-radius: 140px;
    }
    .parameter-setting {
      position: absolute;
      top: 65px;
      left: 192px;
      width: 230px;
      height: 230px;
      background-color: $colorK;
      border-radius: 230px;
      // border: px solid $colorL;
      box-sizing: border-box;
      .target-setting {
        position: absolute;
        left: 0px;
        top: 0px;
        border-radius: 115px 0 0;
        width: 115px;
        height: 115px;
        background: $colorK;
        border: 1px solid $colorL;
        box-sizing: border-box;
      }
      .player-setting {
        position: absolute;
        left: 115px;
        top: 0px;
        border-radius: 0 115px 0 0;
        width: 115px;
        height: 115px;
        background: $colorK;
        border: 1px solid $colorL;
        box-sizing: border-box;
      }
      .group-setting {
        position: absolute;
        left: 0px;
        top: 115px;
        border-radius: 0 0 0 115px;
        width: 115px;
        height: 115px;
        background: $colorK;
        border: 1px solid $colorL;
        box-sizing: border-box;
      }
      .max-setting {
        position: absolute;
        left: 115px;
        top: 115px;
        border-radius: 0 0 115px 0;
        width: 115px;
        height: 115px;
        background: $colorK;
        border: 1px solid $colorL;
        box-sizing: border-box;
      }

      .data-display {
        position: absolute;
        top: 64px;
        left: 67px;
        width: 100px;
        height: 100px;
        background-color: $colorK;
        border-radius: 100px;
        border: 1px solid $colorL;
        box-sizing: border-box;
      }
    }
    .load-weight {
      position: absolute;
      top: 174px;
      left: 430px;
      width: 140px;
      height: 140px;
      background-color: $colorK;
      border-radius: 140px;
      box-sizing: border-box;
    }
  }
}
</style>