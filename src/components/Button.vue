<template>
  <button type="button">Order Now</button>
</template>

<script>
export default {
  name: "Button",
  
};
</script>

<style scoped>
button {
  font-family: "Noto Sans", sans-serif;
  font-size: 2rem;
  border-radius: 1rem;
  border: none;
  background-color: #FF4900;
  color: #fff;
  padding: 0.4rem 2.2rem;
  cursor: pointer;
}

button:hover {
  background-color: #fc7039;
  transition: 0.5s;
}
</style>
