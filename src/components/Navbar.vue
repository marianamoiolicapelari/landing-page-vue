<template>
  <nav class="nav">
    <router-link class="nav-link active" to="/">Home</router-link> 
    <router-link class="nav-link" to="/about">About</router-link> 
    <a class="nav-link" href="/#">Menu</a> 
    <a class="nav-link" href="/#">Blog</a> 
    <a class="nav-link" href="/#">Shop</a> 
    <a class="nav-link" href="/#">Contact</a> 
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
/* nav a {
  margin: 20px;
  text-decoration: none;
  color: #1D2440;
  font-size: 1.5rem;
} */
</style>
