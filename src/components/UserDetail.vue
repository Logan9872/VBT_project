<template>
  <div class="user-select">
    <div class="contrainer">
      <div class="user-topbar">
        <span>用户信息</span>
      </div>
      <div class="user-infor">
        <ul>
          <li></li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "user-detail",
};
</script>
<style lang="scss">
@import "./../assets/scss/confing.scss";
@import "./../assets/scss/base.scss";
.user-select {
  position: absolute;
  top: 60px;
  left: 0px;
  width: 184px;
  height: 579px;
  background-color: $colorF;
  text-align: center;
  left: 0px;
  line-height: 20px;
  .contrainer {
    .user-topbar {
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
        // border: 1px solid rgba(255, 255, 255, 100);
      }
    }
    .user-infor {
      position: absolute;
    }
  }
}
</style>