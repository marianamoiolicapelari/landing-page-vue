<template>
  <div id="our-branches" class="our-branches">
    <h2>Our Branches</h2>
    <div class="our-branches-countries">
      <div class="new-york">
        <img src="../../public/img/City1.png" alt="" />

        <div class="title">
          <div class="img">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="title-img">
            <h4>New York</h4>
          </div>
        </div>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliq ua. Ut enim
          ad minim veniam, quis nostr ud exercitation.
        </p>
      </div>
      <div class="texas">
        <img src="../../public/img/City2.png" alt="" />

        <div class="title">
          <div class="img">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="title-img">
            <h4>Texas</h4>
          </div>
        </div>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliq ua. Ut enim
          ad minim veniam, quis nostr ud exercitation.
        </p>
      </div>
      <div class="new-jersy">
        <img src="../../public/img/City3.png" alt="" />

        <div class="title">
          <div class="img">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="title-img">
            <h4>New Jersy</h4>
          </div>
        </div>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliq ua. Ut enim
          ad minim veniam, quis nostr ud exercitation.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OurBranches",
};
</script>

<style scoped>
.our-branches {
  display: flex;
  flex-direction: column;
  padding: 4rem;
}

.our-branches h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 4rem;
}

.our-branches-countries {
  display: flex;
  justify-content: space-around;
}

.new-york,
.texas,
.new-jersy {
  width: 25%;
  background-color: #253d6b;
  box-shadow: 5px 5px 10px 0px rgb(89, 88, 88);
  margin-bottom: 3rem;
}

.new-york img,
.texas img,
.new-jersy img {
  width: 100%;
}

.new-york h4,
.texas h4,
.new-jersy h4 {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.5rem;
  color: #fff;
  padding: 1rem 0;
  z-index: 1;
}

.title {
  display: flex;
  position: relative;
}

.img {
  position: relative;
  top: 1rem;
  left: -1.1rem;
}

.title-img {
  position: absolute;
  top: 0.7rem;
  left: 1.3rem;
}

.new-york p,
.texas p,
.new-jersy p {
  font-family: "Noto Sans", sans-serif;
  font-size: 1rem;
  color: #fff;
  text-align: center;
  line-height: 2rem;
  margin: 1.1rem;
  padding: 1.5rem 1rem;
  background-color: #151a2f;
}
</style>
