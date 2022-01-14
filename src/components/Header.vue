<template>
  <div class="header">
    <div class="header__container">
      <a class="omega-logo" href="#"><img src="./svg/Omega.svg" /></a>
      <div class="header__nav-bar">
        <a href="#" class="header__link">Demos</a>
        <a href="#" class="header__link">Pages</a>
        <a href="#" class="header__link">Support</a>
      </div>
      <a href="#">
        <svg
          class="burger-icon"
          fill="#000000"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 50 50"
          width="50px"
          height="50px"
        >
          <path
            d="M 0 7.5 L 0 12.5 L 50 12.5 L 50 7.5 Z M 0 22.5 L 0 27.5 L 50 27.5 L 50 22.5 Z M 0 37.5 L 0 42.5 L 50 42.5 L 50 37.5 Z"
          />
        </svg>
      </a>
      <a href="#" class="header__button button">Get this app</a>
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
.header__container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  margin-top: 17px;
}
.omega-logo {
  margin-left: 36px;
}
.omega-logo:hover {
  opacity: 0.5;
}
.header__nav-bar {
  display: flex;
  align-items: center;
  margin-left: auto;
  margin-right: 30px;
}
.header__link {
  padding: 0 20px;
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
.header__button {
  width: 141px;
  height: 45px;
  font-weight: 500px;
  margin-right: 11px;
  margin-left: 13px;
}
.header__link:hover {
  color: #f04037;
}
.burger-icon {
  width: 30px;
  display: none;
}
@media (max-width: 615px) {
  .header__container {
    padding: 0px 20px 20px 20px;
  }
  .omega-logo {
    margin-left: 0px;
  }
  .header__nav-bar {
    display: none;
  }
  .burger-icon {
    display: block;
    width: 45px;
    height: 45px;
  }
  .burger-icon:hover {
    opacity: 0.5;
  }
  .header__button {
    display: none;
  }
}
</style>