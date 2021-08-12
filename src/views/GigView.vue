<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12 col-xl-7 col-12 col-md-12 col-sm-12">
        <GigLeftView />
      </div>
      <div class="col-lg-4 col-sm-12 col-md-12 offset-md-1 offset-lg-1">
        <GigRightView class="gigright" />
      </div>
    </div>
  </div>
</template>

<script>
import GigLeftView from "../components/GigLeftView.vue";
import GigRightView from "../components/GigRightView.vue";

export default {
  components: {
    GigLeftView,
    GigRightView,
  },
};
</script>,
    

<style scoped>
@media (max-width: 1200px) {
  .gigright {
    display: none;
  }
}
</style>
