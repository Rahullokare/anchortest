<template>
  <div>
    <TopBar />
    <GigView />
  </div>
</template>

<script>
import TopBar from "./components/TopBar/TopBar.vue";
import GigView from "./views/GigView.vue";
// import GigProfile from "./views/GigProfile.vue";
export default {
  components: {
    TopBar,
    GigView,
  },
};
</script>

<style></style>
