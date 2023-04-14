<template>
  <footer>
    <section id="footer_top">
      <div class="container d-flex justify-content-between align-items-center">
        <div id="links" class="d-flex text-light">
          <div>
            <h4>DC COMICS</h4>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <h4>SHOP</h4>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div class="mx-5">
            <h4>DC</h4>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy (New)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div>
            <h4>SITES</h4>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
        <div>
          <img class="bg_logo_footer" height="400" src="../assets/img/dc-logo-bg.png" alt="DC Logo BG"/>
        </div>
      </div>
    </section>
    <div class="py-5 bg_footer">
      <div class="container d-flex justify-content-between align-items-center">
        <button>SIGN-UP NOW!</button>
        <div class="d-flex align-items-center">
          <h4 class="m-0 me-5 blue_c">FOLLOW US</h4>
          <ul class="d-flex align-items-center">
            <li>
              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="" />
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "SiteFooter",
};
</script>

<style scoped lang="scss">
#footer_top {
  background-image: url("../assets/img/footer-bg.jpg");
  overflow: hidden;
}

ul {
  list-style: none;
  padding: 0;
  gap: 1rem;
  margin: 0;
}

a {
  text-decoration: none;
  color: grey;
}

.bg_footer {
  background-color: rgb(48, 48, 48);
}

.bg_logo_footer {
  scale: 1.5;
  transform-origin: 100% 50%;
}
.blue_c {
  color: #0282f9;
}

button {
  padding: 0.5rem 1rem;
  border: solid 3px #0282f9;
  background-color: transparent;
  color: white;
}
/* #Endregion Footer  */
</style>
