<template>
  <div>
    <div class="continer">
      <nav-header></nav-header>
      <!-- <user-detail></user-detail>
      <realtime-data></realtime-data>
      <tra-model></tra-model>
      <tra-parameter></tra-parameter> -->
    </div>
  </div>
</template>
<script>
import NavHeader from "./../components/NavHeader";
// import UserDetail from "./../components/UserDetail";
// import TrainingModel from "./../components/TrainingModel";
// import RealTimeData from "./../components/RealTimeData";
// import TrainingParameter from "./../components/TrainingParameter";
export default {
  name: "nav-home",
  components: {
    NavHeader,
    // UserDetail,
    // TrainingModel,
    // RealTimeData,
    // TrainingParameter,
  },
};
</script>

<style lang="scss">
@import "./../assets/scss/confing.scss";
.continer {
  background-color: $colorC;
}
</style>