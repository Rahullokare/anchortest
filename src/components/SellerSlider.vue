<template>
  <div class="gig__imgslider">
    <div
      id="carouselExampleControls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../assets/slider-img.png"
            class="d-block w-100 gig-img"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="../assets/slider-img.png"
            class="d-block w-100 gig-img"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="../assets/slider-img.png"
            class="d-block w-100 gig-img"
            alt="..."
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.carousel-inner .item {
  height: 500px;
  background-size: cover;
  background-position: center center;
}
.gig__imgslider {
  width: 83%;
}
.gig-img {
  height: 450px;
}
</style>
