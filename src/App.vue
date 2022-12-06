<template>
  <TheHeader />
  <router-view />
  <FirstSection />
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import FirstSection from "@/components/FirstSection.vue"

export default {
  components: {
    TheHeader,
    FirstSection
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
