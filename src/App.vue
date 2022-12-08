<template>
  <TheHeader />
  <FirstSection />
  <SecondSection />
  <ThirdSection />
  <CustomerReviews />
  <OpeningHours />
  <OurBranches />
  <TheFooter />
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import FirstSection from "@/components/FirstSection.vue";
import SecondSection from "@/components/SecondSection.vue";
import ThirdSection from "@/components/ThirdSection.vue";
import CustomerReviews from "@/components/CustomerReviews.vue";
import OpeningHours from "@/components/OpeningHours.vue";
import OurBranches from "@/components/OurBranches.vue";
import TheFooter from "@/components/TheFooter.vue";

export default {
  components: {
    TheHeader,
    FirstSection,
    SecondSection,
    ThirdSection,
    CustomerReviews,
    OpeningHours,
    OurBranches,
    TheFooter,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
