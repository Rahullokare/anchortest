<template>
  <div class="seller-profile d-flex align-items-start">
    <img
      class="rounded-circle d-inline"
      src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
      alt="seller"
      height="32"
      width="32"
    />&nbsp;
    <p class="d-inline">Elizabeth Keen</p>
    <div class="rating-div d-inline ml-3">
      <img src="../assets/star.svg" class="rating" alt="rating" />&nbsp;
      <img src="../assets/star.svg" class="rating" alt="rating" />&nbsp;
      <img src="../assets/star.svg" class="rating" alt="rating" />&nbsp;
      <img src="../assets/star.svg" class="rating" alt="rating" />&nbsp;
      <img src="../assets/star.svg" class="rating" alt="rating" />
      <p class="d-inline" style="color: #ffb33e">
        5 <span style="color: #95979d; font-weight: 400">(200)</span>
      </p>
      <p class="queue d-inline">| 2 Orders in Queue</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.d-inline {
  font-weight: 700;
  color: #404145;
}
.queue {
  color: #95979d;
  font-weight: 400;
}
.rating-div img {
  padding-left: 4px;
}
</style>