<template>
  <div class="rt-data">
    <div class="contrainer">
      <div class="RTV-table"></div>
      <div class="MV-table"></div>
      <div class="path-table"></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "realtime-data",
};
</script>
<style lang="scss">
@import "./../assets/scss/confing.scss";
.rt-data {
  .contrainer {
    .RTV-table {
      position: absolute;
      top: 433px;
      left: 200px;
      width: 198px;
      height: 178px;
      background-color: $colorG;
    }
    .MV-table {
      position: absolute;
      top: 433px;
      left: 414px;
      width: 198px;
      height: 178px;
      background-color: $colorG;
    }
    .path-table {
      position: absolute;
      top: 433px;
      left: 628px;
      width: 198px;
      height: 178px;
      background-color: $colorG;
    }
  }
}
</style>