<template>
  <div class="footer">
    <div class="footer__container">
      <div class="footer__container-content">
        <a class="omega-logo" href="#"><img src="./svg/Omega.svg" /></a>
        <div class="footer__links-resp">
          <a class="footer-link" href="#">Support</a>
          <a class="footer-link" href="#">Privacy Policy</a>
          <a class="footer-link" href="#">Terms and Conditions</a>
        </div>
        <div class="footer__copyright">© 2020 UXTheme, All Rights Reserved</div>
        <div class="footer__links">
          <a class="footer-link" href="#">Support</a>
          <a class="footer-link" href="#">Privacy Policy</a>
          <a class="footer-link" href="#">Terms and Conditions</a>
        </div>
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
.footer__container {
  border-top: 1px solid #d8d8d8;
  margin-top: 120px;
  width: 100%;
}
.footer__container-content {
  display: flex;
  align-items: center;
  max-width: 1140px;
  margin: 40px auto;
  padding: 0px 20px 0px 20px;
}
.omega-logo:hover {
  opacity: 0.6;
}
.footer__copyright {
  margin-left: 41px;
  letter-spacing: -0.5px;
}
.footer__links {
  display: flex;
  justify-content: space-between;
  width: 355px;
  margin-left: auto;
  letter-spacing: -0.5px;
}
.footer__links-resp {
  display: none;
}
.footer-link:hover {
  transition: 0.2s;
  opacity: 0.6;
}
.burger-icon {
  display: none;
}

@media (max-width: 828px) {
  .footer__container-content {
    flex-direction: column;
    margin-top: 20px;
  }
  .footer__copyright {
    margin-left: 0px;
    margin-top: 8px;
    font-size: 12px;
  }
  .footer__links {
    display: none;
  }
  .footer__links-resp {
    display: block;
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    width: 355px;
    letter-spacing: -0.5px;
    padding: 0px 20px 0px 20px;
    margin-top: 10px;
  }
}
@media (max-width: 360px) {
  .footer__links-resp {
    width: 300px;
    font-size: 12px;
    margin-top: 5px;
  }
  .footer__copyright {
    font-size: 10px;
  }
}
</style>