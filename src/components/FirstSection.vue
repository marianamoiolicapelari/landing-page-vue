<template>
  <div class="first-section">
    <div class="first-section-left">
      <h2>Dark Coffees</h2>
      <Button />
    </div>

    <div class="first-section-center">
      <img class="coffee" src="../../public/img/Coffee1.png" alt="" />
    </div>
    <div class="first-section-right">
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
  name: "FirstSection",
  components: {
    Button,
  },
};
</script>

<style scoped>
.first-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  background-color: #fefbfa;
  background-image: url("../../public/img/Shape.png");
  background-repeat: no-repeat;
  /* background-size: contain; */
  background-position: right;
}

.first-section-left {
  width: 350px;
  margin-left: 3rem;
}

.first-section-left h2 {
  width: 350px;
  font-family: "Cormorant Upright", serif;
  font-style: italic;
  color: #1d2440;
  font-size: 7.5rem;
  line-height: 6.5rem;
  padding-bottom: 6rem;
}

.first-section-right {
  width: 600px;
}

.first-section-right p {
  color: #fff;
  font-family: 'Noto Sans', sans-serif; 
  font-weight: 100;
  text-align: right;
  line-height: 2.2rem;
 padding-right: 3rem;
 font-size: 1.5rem;
}
</style>
