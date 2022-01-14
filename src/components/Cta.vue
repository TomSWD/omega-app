<template>
  <div class="cta">
    <div class="cta__container">
      <h2 class="cta__heading">Get the app now</h2>
      <p class="cta__text">
        Create custom landing pages with Omega that converts <br />
        more visitors than any website.
      </p>
      <div class="cta__buttons">
        <a
          href="https://www.apple.com/pl/app-store/"
          target="__blank"
          title="App Store"
        >
          <img class="app-store" src="@/assets/img/App Store.png"
        /></a>
        <a
          href="https://play.google.com/store?hl=pl"
          target="__blank"
          title="Play Store"
        >
          <img class="play-store" src="@/assets/img/Play Store.png" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cta",
  components: {},
};
</script>

<style scoped>
.cta__container {
  display: flex;
  align-items: center;
  flex-direction: column;
  max-width: 668px;
  margin: 95px auto;
  padding: 0px 20px 0px 20px;
}
.cta__text {
  text-align: center;
}
.cta__buttons {
  display: flex;
  justify-content: space-between;
  max-width: 436px;
  height: 66px;
  margin-top: 30px;
  gap: 18px;
}
@media (max-width: 465px) {
  .cta__container {
    margin-top: 20px;
  }
  .cta__buttons {
    flex-direction: column;
  }
  .cta__heading {
    text-align: center;
  }
}
</style>