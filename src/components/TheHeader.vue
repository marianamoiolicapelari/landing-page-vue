<template>
  <div class="d-flex justify-content-around p-5 bg-secondary">
    <Navbar />
    <div>
      <p>CoffeeCup</p>
      <img src="../../public/img/LogoWhite.png" alt="" />
    </div>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>

<style scoped>

</style>
