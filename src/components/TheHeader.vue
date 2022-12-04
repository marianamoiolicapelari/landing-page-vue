<template>
  <div class="header">
    <Navbar />
    <div class="header-informations">
      <h1>Coffee</h1>
      <h3>Everything You Love About Coffee</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam.
      </p>
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

.header {
  width: 100%;
  height: 100vh;
  background-image: url("../../public/img/Background.png");
  background-size: 100%;
  background: cover;
  background-position-y: -2rem;
  background-repeat: no-repeat;
}

.header-informations {
  width: 800px;
  margin-left: 3rem;
}

.header-informations h1{
font-family: 'Cormorant Garamond', serif; 
color: #1d2440;
font-size: 10rem;
}

.header-informations h3{
font-family: "Roboto", sans-serif; 
color: #FF540E;
font-size: 3rem;
margin-top: 2rem;
}

.header-informations p{
font-family: "Roboto", sans-serif; 
color: #1d2440;
font-size: 1.5rem;
margin-top: 2rem;
}




</style>
