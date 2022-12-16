<template>
  <div id="second-section" class="second-section">
    <div class="second-section-left">
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

    <div class="second-section-center">
      <div class="coffee">
        <img class="coffee" src="../../public/img/Coffee2.png" alt="" />
      </div>
      <div class="detail">
        <img class="coffee" src="../../public/img/Ellipse.png" alt="" />
      </div>
    </div>
    <div class="second-section-right">
      <h2>Cold Coffees</h2>
      <Button />
    </div>
  </div>
</template>

<script>
import Button from "@/components/Button.vue";
export default {
  name: "SecondSection",
  components: {
    Button,
  },
};
</script>

<style scoped>
.second-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  background-color: #fefbfa;
  background-image: url("../../public/img/Shape1.png");
  background-repeat: no-repeat;
  background-size: 53%;
}

.second-section-left {
 width: 415px;
}

.second-section-left p {
  color: #fff;
  font-family: "Noto Sans", sans-serif;
  font-weight: 100;
  text-align: left;
  line-height: 2.2rem;
  margin-left: 4rem;
  font-size: 1rem;
}

.second-section-center {
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  margin-right:3rem;
}

.coffee {
  position: relative;
  z-index: 1;
}

.detail {
  position: absolute;
  z-index: 0;
}

.second-section-right {
  width: 350px;
  margin-right: 4rem;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.second-section-right h2 {
  width: 350px;
  font-family: "Cormorant Upright", serif;
  font-style: italic;
  color: #1d2440;
  font-size: 6rem;
  line-height: 6.5rem;
  text-align: right;
  padding-bottom: 6rem;
}
</style>
