<template>
  <a href="#" class="header__button button">Get this app</a>
</template>

<script>
export default {
  name: "Button",
  components: {},
};
</script>

<style scoped>
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
}
</style>