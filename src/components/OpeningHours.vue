<template>
  <div class="opening-hours">
    <h2>We are Open</h2>
    <div class="opening-hours-week">
      <p>Monday - Friday</p>
      <p>8:00 am - 11:30 pm</p>
    </div>
    <div class="opening-hours-weekend">
      <p>Saturday and Sunday</p>
      <p>9:00 am - 10:30 pm</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "OpeningHours",
};
</script>

<style scoped>
.opening-hours {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 1.5rem 0 3rem 0;
}

.opening-hours h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 2rem;
}

.opening-hours-week,
.opening-hours-weekend {
  width: 35%;
  padding: 4rem;
  margin: 2rem;
  color: #FFF;
  font-size: 2rem;
  text-align: center;
  font-family: "Noto Sans", sans-serif;
  background-color: #233e6a;
  box-shadow: 5px 5px 10px 0px rgb(104, 102, 102);
}
</style>
