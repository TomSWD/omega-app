<template>
  <div class="content03">
    <div class="content03__container">
      <div class="content03__left-section">
        <h2 class="content03__heading">Improving your travel experience.</h2>
        <p class="content03__text">
          Create custom landing pages with Omega that converts more visitors
          than any website. With lots of unique blocks, you can easily build a
          page without coding.
        </p>
        <a href="#" class="content03__button button">Get this app</a>
      </div>
      <img class="iphone-3" src="@/assets/img/iPhone3.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Content03",
  components: {},
};
</script>

<style scoped>
.content03__container {
  display: flex;
  align-items: center;
  max-width: 1075px;
  padding: 0px 20px 0px 20px;
  margin: auto;
}
.content03__left-section {
  max-width: 548px;
  padding-right: 20px;
}
.content03__text {
  max-width: 515px;
  letter-spacing: -0.8px;
}
.button {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  background-color: #f04037;
  border-radius: 5px;
}
.button:hover {
  transition: 0.2s;
  background-color: #c31a12;
}
.content03__button {
  width: 200px;
  height: 60px;
  font-size: 21px;
  line-height: 27px;
  margin-top: 40px;
}
.iphone-3 {
  margin-top: 10px;
  margin-left: auto;
}

@media (max-width: 900px) {
  .content03__container {
    flex-direction: column;
    text-align: center;
    margin-top: -20px;
  }
  .content03__button {
    width: 100%;
  }
  .content03__left-section {
    padding-right: 0px;
  }
  .iphone-3 {
    margin: 45px auto;
  }
}
</style>