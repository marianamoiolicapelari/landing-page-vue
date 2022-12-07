<template>
  <div class="third-section">
    <div class="third-section-left">
      <h2>Hot Coffees</h2>
      <Button />
    </div>

    <div class="third-section-center">
      <img class="coffee" src="../../public/img/Coffee3.png" alt="" />
    </div>
    <div class="third-section-right">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipis cing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ea
        commodo consequat. Duis aut dolor in reprehenderit in voluptate velit
        esse cillum dolore eu fugiat nulla pariatur. Excepteur occaecat
        cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
        id est laborum
      </p>
    </div>
  </div>
</template>

<script>
import Button from "@/components/Button.vue";
export default {
  name: "ThirdSection",
  components: {
    Button,
  },
};
</script>

<style scoped>
.third-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  background-color: #fefbfa;
  background-image: url("../../public/img/Shape2.png");
  background-repeat: no-repeat;
  background-position: right;
}

.third-section-left {
  width: 350px;
  margin-left: 3rem;
}

.third-section-left h2 {
  width: 350px;
  font-family: "Cormorant Upright", serif;
  font-style: italic;
  color: #1d2440;
  font-size: 8rem;
  line-height: 7rem;
  padding-bottom: 6rem;
}

.third-section-center {
  width: 300px;
}

.third-section-right {
  width: 500px;
}

.third-section-right p {
  color: #fff;
  font-family: "Noto Sans", sans-serif;
  font-weight: 100;
  text-align: right;
  line-height: 2.2rem;
  padding-right: 3rem;
  font-size: 1.3rem;
}
</style>
