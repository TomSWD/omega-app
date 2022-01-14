<template>
  <div class="content02">
    <div class="content02__container">
      <div class="content02__left-section">
        <div class="content02__pic-column">
          <div class="content02__pic-column-1">
            <img class="pic-1" src="@/assets/img/Section02-pic1.png" />
            <img class="pic-2" src="@/assets/img/Section02-pic2.png" />
          </div>
          <div class="content02__pic-column-2">
            <img class="pic-3" src="@/assets/img/Section02-pic3.png" />
            <img class="pic-4" src="@/assets/img/Section02-pic4.png" />
          </div>
        </div>
      </div>
      <div class="content02__right-section">
        <h2 class="content02__heading">See the world & spend less always.</h2>
        <p class="content02__text">
          Create custom landing pages with Omega that converts more visitors
          than any website. With lots of unique blocks, you can easily biuld a
          page without coding.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content02",
  components: {},
};
</script>

<style scoped>
.content02__container {
  display: flex;
  align-items: center;
  max-width: 1145px;
  margin: 90px auto;
  padding: 0px 0px 0px 20px;
}
.content02__pic-column {
  align-self: center;
  display: flex;
  flex-direction: row;
  height: 555px;
  max-width: 475px;
  gap: 15px;
  padding-right: 20px;
}
.content02__pic-column-1,
.content02__pic-column-2 {
  display: flex;
  flex-direction: column;
}
.content02__pic-column-2 {
  align-self: flex-end;
}
.pic-1,
.pic-3 {
  margin-bottom: 15px;
}
.content02__right-section {
  display: flex;
  flex-direction: column;
  max-width: 528px;
  margin-top: 50px;
  margin-left: auto;
}
@media (max-width: 950px) {
  .content02__container {
    flex-direction: column;
    text-align: center;
    margin: 50px auto;
  }
  .content02__pic-column {
    padding-right: 0px;
    height: auto;
  }
  .content02__right-section {
    margin: 30px auto;
  }
}
@media (max-width: 485px) {
  .content02__pic-column {
    flex-direction: column;
    margin: -30px auto;
  }
  .content02__pic-column-1,
  .content02__pic-column-2 {
    align-self: flex-start;
    align-self: center;
  }
  .content02__right-section {
    align-self: center;
    margin: auto;
    padding-top: 40px;
  }
}
@media (max-width: 460px) {
  .content02__right-section {
    padding-top: 40px;
  }
}
</style>