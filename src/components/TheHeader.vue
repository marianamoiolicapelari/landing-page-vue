<template>
  <div id="header" class="header">
    <Navbar />
    <div class="header-informations">
      <h1>Coffee</h1>
      <h3>Everything You Love About Coffee</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do <br />
        eiusmod tempor incididunt ut labore et dolore magna aliqua. <br />
        Ut enim ad minim veniam.
      </p>
    </div>
    <Button class="btn-header" />
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Button from "../components/Button.vue";
export default {
  components: {
    Navbar,
    Button,
  },
};
</script>

<style scoped>
.header {
  width: 100%;
  background-image: url("../../public/img/Background.png");
  background-position: 100%;
  background-repeat: no-repeat;
}

.header-informations {
  width: 800px;
  margin-left: 4rem;
}

.header-informations h1 {
  font-family: "Cormorant Upright", serif;
  font-weight: 100;
  font-style: italic;
  color: #1d2440;
  font-size: 9rem;
}

.header-informations h3 {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
  color: #ff540e;
  font-size: 2rem;
  margin-top: 4rem;
}

.header-informations p {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
  color: #1d2440;
  font-size: 0.9rem;
  margin-top: 2rem;
}

.btn-header {
  margin: 3.6rem 4rem;
}
</style>
