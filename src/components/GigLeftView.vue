<template>
  <div class="gigleft__view">
    <p class="mt-5 pb-3 gig__heading">
      I will design modern mobile app or web app UI UX in figma or adobe xd
    </p>
    <SellersProfile />
    <SellerSlider />
    <AboutGig />
    <GigRightView class="right" />
    <AboutSeller />
    <ComparePackages />
    <RecommendSellers />
    <Faq />

    <CommentSection />

    <CommentSection />
    <CommentSection />
    <MoreServices />
  </div>
</template>

<script>
import AboutGig from "./AboutGig.vue";
import AboutSeller from "./AboutSeller.vue";
import CommentSection from "./CommentSection.vue";
import ComparePackages from "./ComparePackages.vue";
import Faq from "./Faq.vue";
import GigRightView from "./GigRightView.vue";
import MoreServices from "./MoreServices.vue";
import RecommendSellers from "./RecommendSellers.vue";
import SellerSlider from "./SellerSlider.vue";
import SellersProfile from "./SellersProfile.vue";
export default {
  components: {
    SellersProfile,
    AboutGig,
    SellerSlider,
    RecommendSellers,
    AboutSeller,
    ComparePackages,
    Faq,
    CommentSection,
    MoreServices,
    GigRightView,
  },
};
</script>

<style scoped>
.right {
  display: none;
}
@media (max-width: 1200px) {
  .right {
    display: block;
  }
}
.gigleft__view {
  padding-bottom: 40px;
}
.gig__heading {
  font-size: 28px;
  font-weight: 700;
  color: #404145;
}
</style>
