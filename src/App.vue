<template>
  <div>
    <Header />
    <Hero />
    <Testimonial />
    <Content01 />
    <Content02 />
    <Content03 />
    <Video />
    <Cta />
    <Footer />
  </div>
</template>

<script>
import "@/assets/styles/reset.css";
import "@/assets/styles/global.css";

import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Testimonial from "./components/Testimonial.vue";
import Content01 from "./components/Content01.vue";
import Content02 from "./components/Content02.vue";
import Content03 from "./components/Content03.vue";
import Video from "./components/Video.vue";
import Cta from "./components/Cta.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Hero,
    Testimonial,
    Content01,
    Content02,
    Content03,
    Video,
    Cta,
    Footer,
  },
};
</script>

<style>
@font-face {
  font-family: "Circular Std Book";
  src: url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.eot");
  src: url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/860c3ec7bbc5da3e97233ccecafe512e.svg#Circular Std Book")
      format("svg");
}
@font-face {
  font-family: "Circular Std Bold";
  src: url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.eot");
  src: url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/961a181da27e7cbc072ec2fb5bbfe2a9.svg#Circular Std Bold")
      format("svg");
}
@font-face {
  font-family: "Circular Std Medium";
  src: url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.eot");
  src: url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/9475d6a0b79c164f9f605673714e75d9.svg#Circular Std Medium")
      format("svg");
}
</style>
