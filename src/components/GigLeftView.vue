<template>
  <div class="gigleft__view">
    <p class="mt-5 pb-3 gig__heading">
      I will design modern mobile app or web app UI UX in figma or adobe xd
    </p>
    <SellersProfile />
    <SellerSlider />
    <AboutGig />
    <AboutSeller />
    <ComparePackages />
    <RecommendSellers />
    <Faq />
    <CommentSection />

    <CommentSection />
    <CommentSection />
  </div>
</template>

<script>
import AboutGig from "./AboutGig.vue";
import AboutSeller from "./AboutSeller.vue";
import CommentSection from "./CommentSection.vue";
import ComparePackages from "./ComparePackages.vue";
import Faq from "./Faq.vue";
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
  },
};
</script>

<style scoped>
.gigleft__view {
  padding-bottom: 40px;
}
.gig__heading {
  font-size: 28px;
  font-weight: 700;
  color: #404145;
}
</style>
