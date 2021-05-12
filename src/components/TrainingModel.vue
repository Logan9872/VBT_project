<template>
  <div class="tra-model">
    <div class="contrainer">
      <div class="tra-topbar">
        <span>模式选择</span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "tra-model",
};
</script>
<style lang="scss">
@import "./../assets/scss/confing.scss";
@import "./../assets/scss/base.scss";
.tra-model {
  position: absolute;
  top: 60px;
  left: 840px;
  width: 184px;
  height: 580px;
  line-height: 20px;
  background-color: $colorF;
  text-align: center;
  .contrainer {
    .tra-topbar {
      position: relative;
      text-align: center;
      span {
        display: inline-block;
        position: absolute;
        left: 0px;
        width: 184px;
        height: 57px;
        color: $colorI;
        background-color: $colorE;
        font-size: $fontE;
        font-weight: $font-weightA;
        text-align: center;
        cursor: pointer;
        padding-top: 18px;
        box-sizing: border-box;
      }
    }
  }
}
</style>