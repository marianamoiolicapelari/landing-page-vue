<template>
  <div class="navbar">
    <nav class="navbar-links">
      <a class="navbar-color" href="/#header">Home</a>
      <a class="navbar-color" href="/#customer-reviews">About</a>
      <a class="navbar-color" href="/#first-section">Menu</a>
      <a class="navbar-color" href="/#our-branches">Blog</a>
      <a class="navbar-color" href="/#second-section">Shop</a>
      <a class="navbar-color" href="/#contact">Contact</a>
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
  padding: 8rem 1.5rem 3rem 4rem;
  font-family: "Roboto", sans-serif;
  font-size: 1.7rem;
  position: relative;
}

.navbar-links a {
  padding-right: 4rem;
  text-decoration: none;
  color: #1d2440;
}

.navbar-logo {
  display: flex;
  width: 100px;
  align-items: center;
  margin-right: 8rem;
  position: absolute;
  right: 2.5rem;

}

.navbar-logo p {
  margin: 0rem 5rem 0rem 0.5rem;
  color: #fff;
}
</style>
