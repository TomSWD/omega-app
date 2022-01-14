<template>
  <div class="content02__pic-respo">
    <img class="pic-1-respo" src="@/assets/img/Section02-pic1.png" />
    <img class="pic-3-respo" src="@/assets/img/Section02-pic3.png" />
    <img class="pic-4-respo" src="@/assets/img/Section02-pic4.png" />
    <img class="pic-2-respo" src="@/assets/img/Section02-pic2.png" />
  </div>
</template>

<script>
export default {
  name: "PicRespo",
  components: {},
};
</script>

<style scoped>
.content02__pic-respo {
  display: flex;
  flex-direction: column;
  gap: 15px;
  max-width: 490px;
}
.pic-3-respo {
  margin-left: 50px;
}
</style>