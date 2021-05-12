<template>
  <div id="app">
    <NavHeader />
    <UserDetail />
    <TrainingModel />
    <RealTimeData />
    <TrainingParameter />
  </div>
</template>

<script>
import NavHeader from "./components/NavHeader";
import UserDetail from "./components/UserDetail";
import TrainingModel from "./components/TrainingModel";
import RealTimeData from "./components/RealTimeData";
import TrainingParameter from "./components/TrainingParameter";

export default {
  name: "App",
  components: {
    NavHeader,
    UserDetail,
    TrainingModel,
    RealTimeData,
    TrainingParameter,
  },
};
</script>

<style>
</style>
