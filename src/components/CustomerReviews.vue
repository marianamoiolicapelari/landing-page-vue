<template>
  <div id="customer-reviews" class="customer-reviews">
    <h2>Customer Reviews</h2>
    <div class="customer-reviews-info">
      <div class="customer-reviews-info-img">
        <img src="../../public/img/People.png" alt="" />
      </div>
      <div class="customer-reviews-info-text">
        <div class="customer-reviews-info-text-1">
          <h3>John Peter</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea com modo consequat.
          </p>
        </div>

        <div class="customer-reviews-info-text-2">
          <h3>Ella Thomson</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea com modo consequat.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomerReviews.vue",
};
</script>

<style scoped>
.customer-reviews {
  display: flex;
  flex-direction: column;
  padding: 4rem;
}

.customer-reviews h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 2rem;
}

.customer-reviews-info {
  display: flex;
  background-color: #151a2f;
  padding: 2rem;
}

.customer-reviews-info-text {
  display: flex;
  flex-direction: column;
  justify-content: center;

  width: 48%;
  color: #fff;
  text-align: center;
  padding: 2rem;
  margin-left: 3rem;
}

.customer-reviews-info-text-1 h3,
.customer-reviews-info-text-2 h3 {
  font-family: "Cormorant Garamond", serif;
  font-size: 4rem;
  margin-bottom: 2rem;
}

.customer-reviews-info-text-1 p {
  margin-bottom: 3rem;
}

.customer-reviews-info-text-1 p,
.customer-reviews-info-text-2 p {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.5rem;
}
</style>
