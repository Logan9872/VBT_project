<template>
  <div class="header">
    <div class="nav_header">
      <div class="container">
        <div class="header-logo">
          <a href="javascript: ;"
            ><span class="icon-app"></span> 北京体育大学VBT训练系统</a
          >
        </div>
        <div class="table_select">
          <a href="javascript: ;">实时速度</a>
          <a href="javascript: ;">平均速度</a>
          <a href="javascript: ;">运动轨迹</a>
          <a href="javascript: ;">历史训练</a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "nav-header",
};
</script>
<style lang ="scss">
@import "./../assets/scss/confing.scss";
@import "./../assets/scss/reset.scss";
@import "./../assets/scss/mixin.scss";
@import "./../assets/scss/base.scss";

.header {
  .nav_header {
    width: $min-width;
    position: relative;
    height: 60px;
    background-color: $colorC;

    .container {
      a {
        display: inline-block;
        color: $colorI;
        text-decoration: none;
        margin-right: 15px;
      }

      .header-logo {
        position: absolute;
        left: 24px;
        top: 4px;
        width: 260px;
        height: 24px;
        color: $colorI;
        font-size: $fontE;
        font-weight: $font-weightA;
        text-align: center;
        font-family: SourceHanSansSC-regular;
        .icon-app {
          display: inline-block;
          @include bgImg(35px, 35px, "/Imgs/applogo.png");
          text-align: end;
          position: relative;
          top: 12px;
        }
      }
      .table_select {
        position: absolute;
        right: 57px;
        top: 20px;
        height: 20px;
        color: rgba(255, 255, 255, 100);
        font-size: fontE;
        font-weight: $font-weightA;
        text-align: left;

        a {
          display: inline-block;
          width: 70px;
          height: 25px;
          line-height: 20px;
          border-radius: 18px;
          margin-left: 15px;
          padding-top: 5px;
          text-align: center;
          cursor: pointer;

          &:hover {
            background-color: $colorA;
            &:active {
              background-color: $colorB;
            }
          }
          &:focus {
            background-color: $colorA;
          }
        }
      }
    }
  }
}
</style>