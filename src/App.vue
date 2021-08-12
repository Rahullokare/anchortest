<template>
  <div>
    <TopBar />
    <!-- <GigProfile /> -->
    <Slider />
    <Slider />
  </div>
</template>

<script>
import TopBar from "./components/TopBar/TopBar.vue";
// import GigProfile from "./views/GigProfile.vue";
import Slider from "./components/Slider.vue";
export default {
  components: {
    TopBar,
    // GigProfile,
    Slider,
  },
};
</script>

<style></style>
