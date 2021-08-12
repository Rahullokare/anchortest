<template>
  <div class="card rounded" style="width: 14rem">
    <img
      src="https://fiverr-res.cloudinary.com/t_gig_cards_web_x2,q_auto,f_auto/gigs/170521862/original/715f4ac59ea6d6e18415f8bacaa61f1f7d45919e.png"
      class="card-img-top"
      alt="..."
    />
    <div class="card-body">
      <div class="card-title">
        <p class="card-tx">I will be your web developer im</p>
        <img src="../assets/star.svg" alt="" srcset="" />
        <span>5(23 Reviews)</span>
      </div>
      <div class="d-flex">
        <div class="">
          <img
            class="rounded-circle"
            src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
            alt="seller"
            height="32"
            width="32"
          />&nbsp;
        </div>
        <div class="rates">
          <p class="name">Elizabeth Keen</p>
          <p>Marketing Expert</p>
          <p>5 years of experience</p>
          <!-- rating -->
        </div>
      </div>
    </div>
    <div
      class="
        btn
        d-flex
        w-100
        align-items-center
        justify-content-between
        text-white
      "
    >
      <div>
        <i class="far fa-heart"></i>
        <i class="fas fa-bars"></i>
      </div>
      <div class="align-self-center">
        <p class="pricing" style="margin-bottom: 0">
          Starting at <strong>5$</strong>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
i {
  margin-left: 4px;
}
.btn {
  background-color: #1dbf73;
  padding: 10px;
}
.card-tx {
  margin-bottom: 0;
}
.rates p {
  margin-bottom: 0rem;
  color: #4a4a4a;
}
.pricing {
  margin-bottom: 0;
  text-transform: uppercase;
  font-size: 14px;
}
.pricing strong {
  font-size: 20px;
}
</style>