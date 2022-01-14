<template>
  <div class="video">
    <div class="video__container">
      <img class="video-pic" src="@/assets/img/Video-pic.png" />
      <a class="play-btn" href="#">
        <img class="play-icon" src="@/assets/img/play-button.png" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Video",
  components: {},
};
</script>

<style scoped>
.video__container {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  margin-top: 110px;
}
.video-pic {
  position: relative;
}
.play-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  width: 8vw;
  height: 8vw;
  border-radius: 50%;
  background-color: #fff;
}
.play-icon {
  max-width: 2vw;
}
.play-btn:hover {
  transition: 0.5s;
  background-color: #f2f2f2;
  width: 9vw;
  height: 9vw;
}
@media (max-width: 900px) {
  .video__container {
    margin-top: 40px;
  }
}
@media (max-width: 500px) {
  .video__container {
    margin-top: 0px;
  }
}
</style>