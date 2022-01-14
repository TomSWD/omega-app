<template>
  <div class="hero">
    <div class="hero__container">
      <img class="iphone-1" src="@/assets/img/iPhone1.png" />
      <div class="hero__right-section">
        <h2 class="hero__heading">Travel the world & meet new friends.</h2>
        <p class="hero__text">
          Create custom landing pages with Omega that convert more visitors than
          any website. With lots of unique blocks, you can easily build a page
          without coding.
        </p>
        <form class="hero__cta">
          <svg
            class="envelope__icon"
            width="22"
            height="18"
            viewBox="0 0 22 18"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M2 2L11.5 10L21 2"
              stroke="#CDCCD9"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <rect
              x="1"
              y="1"
              width="20"
              height="16"
              rx="2"
              stroke="#CDCCD9"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
          <input
            class="cta__email"
            type="text"
            name="email-address"
            value="Email address"
          />
          <a href="#" class="hero__button button">I want to join</a>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  components: {},
};
</script>

<style scoped>
.hero__container {
  display: flex;
  flex-direction: row;
  align-items: center;
  max-width: 1050px;
  margin: 70px auto 0px;
  padding: 0 20px 0 20px;
}

.hero__right-section {
  display: flex;
  flex-direction: column;
  gap: 30px;
  margin-left: auto;
  max-width: 530px;
}
.hero__text {
  color: #19191b;
  margin-top: 5px;
  width: 100%;
}
.hero__cta {
  display: flex;
  flex-direction: row;
  align-items: center;
  background-color: #fff;
  height: 71px;
  max-width: 475px;
  border: 1px solid #eae9f2;
  border-radius: 10px;
  margin-top: 25px;
}
.envelope__icon {
  margin-left: 18px;
  color: #fff;
}
.cta__email {
  font-family: Circular Std Book;
  border: 0px;
  flex-grow: 1;
  border-radius: 3px;
  color: #696871;
  opacity: 0.5;
  margin-left: 5px;
}
.button {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  background-color: #f04037;
  border-radius: 5px;
  margin-right: 5px;
}
.button:hover {
  transition: 0.2s;
  background-color: #c31a12;
}
.hero__button {
  width: 200px;
  height: 60px;
  font-size: 21px;
  line-height: 27px;
}
@media (max-width: 935px) {
  .hero__container {
    flex-direction: column;
    text-align: center;
    margin-top: 50px;
  }
  .iphone-1 {
    margin: 0 auto;
  }
  .hero__right-section {
    margin: 10px auto;
  }
  .hero__text {
    margin-top: 0px;
  }
  .hero__cta {
    width: 100%;
    align-self: center;
    margin-top: 5px;
  }
}

@media (max-width: 615px) {
  .hero__container {
    margin-top: 15px;
  }
  .hero__cta {
    flex-wrap: wrap;
    padding-top: 20px;
  }
  .button {
    width: 100%;
    margin-right: 0px;
    margin: 20px 0px 0px 0px;
  }
}
@media (max-width: 377px) {
  .envelope__icon {
    display: none;
  }
  .cta__email {
    margin-left: 0px;
    text-align: center;
  }
}
</style>