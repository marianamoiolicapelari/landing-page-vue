<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="../../public/img/LogoWhite.png" alt="" width="65" height="70" />
      <p>CoffeeCup</p>
    </div>
    <div class="footer-information">
      <ul>
        <li class="principal">Information.</li>
        <li>About us</li>
        <li>Branches</li>
        <li>Menu</li>
        <li>Contact</li>
        <li>Map</li>
      </ul>
    </div>
    <div class="footer-contact">
      <ul>
        <li class="principal">Contact Us.</li>
        <li>Support</li>
        <li>your_id@gmail.com</li>
      </ul>
    </div>
  </div>

  <div class="navbar-and-social-media">
    <Navbar class="navbar-footer" />
    <div class="social-media">
      <i class="bi bi-facebook"></i>
      <i class="bi bi-instagram"></i>
      <i class="bi bi-twitter"></i>
      <i class="bi bi-youtube"></i>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  name: "TheFooter",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.footer {
  display: flex;
  background-color: #1d2440;
  padding: 6rem 0 2rem 6rem;
}

.footer-logo {
  display: flex;
  width: 60%;
}

.footer-logo p {
  font-family: "Noto Sans", sans-serif;
  font-size: 3rem;
  color: #fff;
  margin-left: 1rem;
}

.footer-information,
.footer-contact {
  width: 20%;
  font-family: "Roboto", sans-serif;
  color: #fff;
  font-size: 1rem;
}

.footer-information li,
.footer-contact li {
  list-style: none;
  line-height: 2.3rem;
  font-size: 1.4rem;
}

.principal {
  font-size: 2rem !important;
  padding-bottom: 2rem;
  font-weight: bold;
}

.navbar-footer {
  padding: 4rem 0 3rem 6rem;
  background-color: #1d2440;
}

.navbar-and-social-media {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #1d2440;
}

.social-media {
  width: 300px;
  height: 10px;
}

.social-media i {
  color: #ff540e;
  padding: 0 1rem;
  font-size: 1.6rem;
}

:deep(.navbar-color) {
  color: #fff !important;
  font-size: 1.5rem;
}

:deep(.navbar-media-social) {
  display: none;
}
</style>
