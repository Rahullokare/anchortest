<template>
  <div class="container-fluid gigprofile">
    <div class="row">
      <div class="col-7 d-flex justify-content-center">
        <div class="gigprofile__img">
          <p>
            I will be your full stack web developer in react js nodejs firebase
          </p>
          <div class="gigprofile__user">
            <img
              src="https://fiverr-res.cloudinary.com/t_profile_thumb,q_auto,f_auto/attachments/profile/photo/5693cf4f9db5dc367ef4a2eabd326ab1-908547401616923209634/JPEG_20210328_142008_6520848740211920130.jpg"
              alt=""
              class="gigprofile__user--img"
            />
            <p>Elizabeth Keen</p>
          </div>
          <!-- carousel -->
          <div class="gigprofile__slider">
            <div
              id="carouselExampleControls"
              class="carousel slide slider__image"
              data-ride="carousel"
            >
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img
                    class="d-block w-100"
                    src=" https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQNvlondRYQro2kEhdfoS5rG2Xtgl27hHT1rg&usqp=CAU"
                    alt="First slide"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    class="d-block w-100"
                    src=" https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQNvlondRYQro2kEhdfoS5rG2Xtgl27hHT1rg&usqp=CAU"
                    alt="Second slide"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    class="d-block w-100"
                    src=" https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQNvlondRYQro2kEhdfoS5rG2Xtgl27hHT1rg&usqp=CAU"
                    alt="Third slide"
                  />
                </div>
              </div>
              <a
                class="carousel-control-prev"
                href="#carouselExampleControls"
                role="button"
                data-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
                <span class="sr-only">Previous</span>
              </a>
              <a
                class="carousel-control-next"
                href="#carouselExampleControls"
                role="button"
                data-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-5 image__stick">
        <div class="gig__pricing"></div>
      </div>
    </div>
  </div>
</template>

<script>
// import SellerSlider from "../components/SellerSlider.vue";

export default {};
</script>

<style scoped>
/* 
SellerSliderGIGPROFILE IMAGE */
.gigprofile__user--img {
  height: 32px;
  width: 32px;
  border-radius: 50px;
}
.gigprofile {
  margin: 25px 0 0 0;
}
.gigprofile__img {
  width: 87%;
}
.gigprofile__img > p {
  font-size: 28px;
  margin-bottom: 0.5rem;
  font-weight: 700;
}
.gigprofile__user {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.gigprofile__user > p {
  margin-left: 10px;
  margin-bottom: 0;
  font-weight: bold;
}
.gigprofile__slider {
  margin-top: 25px;
  display: flex;
  justify-content: center;
}
.slider__image {
  width: 90%;
  height: 450px;
}
.gigprofile__slider {
  margin-top: 25px;
  display: flex;
  justify-content: center;
}
/* GIGPROFILE IMAGE END */
</style>
