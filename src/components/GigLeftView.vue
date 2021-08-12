<template>
  <div>
    <h1 class="mt-4 pb-3">
      I will design modern mobile app or web app UI UX in figma or adobe xd
    </h1>
    <SellersProfile />
    <SellerSlider />
    <AboutGig />
    <AboutSeller />
    <ComparePackages />
    <RecommendSellers />
    <Faq />
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
  },
};
</script>

<style scoped>
</style>