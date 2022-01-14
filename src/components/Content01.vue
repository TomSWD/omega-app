<template>
  <div class="content01">
    <div class="content01__container">
      <div class="content01__left-section">
        <h2 class="content01__heading">
          Making trip is fun. Travel with friends.
        </h2>
        <p class="content01__text">
          Create custom landing pages with Omega that converts more visitors
          than any website. With lots of unique blocks, you can easily biuld a
          page without coding.
        </p>
        <div class="content01__steps">
          <div class="content01__step">
            <div class="content01__step-number">1</div>
            <div class="content01__step-main">
              <div class="content01__step-description">
                Find your trip partner
              </div>
              <p class="content01__step-txt">
                With lots of unique blocks, you can easily build <br />
                a page without coding. Build your next landing page quickly.
              </p>
            </div>
          </div>
          <div class="content01__step">
            <div class="content01__step-number">2</div>
            <div class="content01__step-main">
              <div class="content01__step-description">
                Plan trip with easy steps
              </div>
              <p class="content01__step-txt">
                With lots of unique blocks, you can easily build <br />
                a page without coding. Build your next landing page quickly.
              </p>
            </div>
          </div>
        </div>
      </div>
      <img class="iphone-2" src="@/assets/img/iPhone2.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Content01",
  components: {},
};
</script>

<style scoped>
.content01__container {
  display: flex;
  flex-direction: row;
  max-width: 1120px;
  margin: 100px auto 80px;
  padding: 0px 20px 0px 20px;
}
.content01__left-section {
  display: flex;
  flex-direction: column;
  max-width: 528px;
  margin-top: 5px;
}
.content01__text {
  max-width: 515px;
  margin-bottom: 40px;
}
.content01__steps {
  display: flex;
  flex-direction: column;
  gap: 32px;
}
.content01__step {
  display: flex;
  flex-direction: row;
  max-width: 431px;
  height: 125px;
}
.content01__step-number {
  color: #fff;
  font-size: 24px;
  line-height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 49px;
  height: 49px;
  border-radius: 50%;
  background-color: #5454d4;
}
.content01__step-main {
  max-width: 323px;
  height: 125px;
  margin-left: auto;
}
.content01__step-description {
  font-size: 21px;
  font-weight: 700;
  line-height: 26px;
}
.content01__step-txt {
  font-size: 16px;
  line-height: 28px;
  color: #696871;
  margin-top: 14px;
}
.iphone-2 {
  margin-left: auto;
}

@media (max-width: 980px) {
  .content01__container {
    flex-direction: column;
    margin-top: 40px;
  }
  .content01__left-section {
    max-width: 750px;
    text-align: center;
    margin: auto;
  }
  .content01__text {
    align-self: center;
  }
  .content01__steps {
    flex-direction: row;
    justify-content: center;
    gap: 10px;
  }
  .content01__step {
    flex-direction: column;
    align-items: center;
    height: auto;
    margin-top: 0px;
    padding: 0px 5px 0px 5px;
  }
  .content01__step-main {
    margin-top: 20px;
  }
  .iphone-2 {
    align-self: center;
    margin-top: 30px;
    margin-left: 0px;
  }
}
@media (max-width: 705px) {
  .iphone-2 {
    margin-top: 60px;
  }
}
@media (max-width: 567px) {
  .content01__steps {
    flex-direction: column;
    align-items: center;
    margin-top: -15px;
    gap: 20px;
  }
  .iphone-2 {
    margin-top: 40px;
  }
}
@media (max-width: 370px) {
  .content01__steps {
    gap: 40px;
  }
}
</style>