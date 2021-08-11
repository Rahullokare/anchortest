<template>
  <div>
    <TopBar />
    <GigProfile />
  </div>
</template>

<script>
import TopBar from "./components/TopBar/TopBar.vue";
import GigProfile from "./views/GigProfile.vue";
export default {
  components: {
    TopBar,
    GigProfile,
  },
};
</script>

<style></style>
