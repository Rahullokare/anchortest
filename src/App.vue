<template>
  <div>
    <TopBar class="topbar-1" />
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

<style>
@media (max-width: 1200px) {
  .topbar-1 {
    display: none;
  }
}
</style>
