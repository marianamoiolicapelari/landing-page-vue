<template>
  <TheHeader />
  <router-view />
  <FirstSection />
  <SecondSection />
  <ThirdSection />
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import FirstSection from "@/components/FirstSection.vue";
import SecondSection from "@/components/SecondSection.vue"
import ThirdSection from "@/components/ThirdSection.vue"

export default {
  components: {
    TheHeader,
    FirstSection,
    SecondSection,
    ThirdSection
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
