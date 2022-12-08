<template>
  <div class="navbar">
    <nav class="navbar-links">
      <router-link class="navbar-color" to="/">Home</router-link>
      <router-link class="navbar-color" to="/about">About</router-link>
      <a class="navbar-color" href="/#">Menu</a>
      <a class="navbar-color" href="/#">Blog</a>
      <a class="navbar-color" href="/#">Shop</a>
      <a class="navbar-color" href="/#">Contact</a>
    </nav>
    <div class="navbar-logo navbar-media-social">
      <img src="../../public/img/LogoWhite.png" alt="" width="35" height="40" />
      <p>CoffeeCup</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8.5rem 3rem 3rem 4rem;
  font-family: "Roboto", sans-serif;
  font-size: 1.8rem;
}

.navbar-links a {
  padding-right: 6rem;
  text-decoration: none;
  color: #1d2440;
}

.navbar-logo {
  display: flex;
  align-items: center;
  padding-left: 2rem;
}

.navbar-logo p {
  margin: 0rem 5rem 0rem 0.5rem;
  color: #FFF;
}

</style>
