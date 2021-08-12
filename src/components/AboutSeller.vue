<template>
  <div style="margin-bottom: 64px">
    <h1 class="pb-5">About The Seller</h1>
    <div class="row pb-4">
      <div class="col-2">
        <img
          class="rounded-circle"
          src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
          alt="seller"
          height="110"
          width="110"
        />&nbsp;
      </div>
      <div class="col-4 rates">
        <p class="name">Elizabeth Keen</p>
        <p>Marketing Expert</p>
        <!-- rating -->
        <div class="rating-div">
          <img src="../assets/star.svg" class="rating" alt="rating" />
          <img src="../assets/star.svg" class="rating" alt="rating" />
          <img src="../assets/star.svg" class="rating" alt="rating" />
          <img src="../assets/star.svg" class="rating" alt="rating" />
          <img src="../assets/star.svg" class="rating" alt="rating" />
          <p class="d-inline" style="color: #ffb33e">
            5 <span style="color: #95979d; font-weight: 400">(200)</span>
          </p>
        </div>

        <div class="btn btn-outline-secondary">Contact Me</div>
      </div>
    </div>
    <!-- seller stats -->
    <div class="stats-desc">
      <div class="row border-bottom">
        <div class="col-6">
          <p>
            From <br />
            <strong>India</strong>
          </p>
        </div>
        <div class="col-6">
          <p>
            Member since<br />
            <strong>May 2021</strong>
          </p>
        </div>
        <div class="w-100"></div>
        <div class="col-6">
          <p>
            Avg. response time<br />
            <strong>1 hour</strong>
          </p>
        </div>
        <div class="col-6">
          <p>
            Last delivery about<br />
            <strong>22 hours</strong>
          </p>
        </div>
      </div>
      <p class="article">
        Hi, I am a creative UI/UX designer with years of experience of designing
        mobile applications and websites in Figma and Adobe XD. I have worked
        with many small to medium-sized businesses in recent years and helped
        them grow. I also have experience of development in React/React Native
        so I know the needs of developers. I love my field, do creative stuff,
        and help businesses. Check through my gigs, shoot me a message, let's
        discuss your requirements, and start working together towards success!
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.article {
  padding-top: 15px;
}
.stats-desc {
  border: 1px solid #dadbdd;
  margin-top: 0;
  border-radius: 3px;
  padding: 24px;
  color: #62646a;
}
.btn {
  margin-top: 20px;
}
h1 {
  font-weight: 500;
  color: #4a4a4a;
  font-size: 20px;
}
.name {
  font-size: 16px;
  font-weight: 700;
  color: #4a4a4a;
}
.rates p {
  margin-bottom: 0rem;
  color: #4a4a4a;
}
.rating-div img {
  padding-left: 4px;
}
</style>