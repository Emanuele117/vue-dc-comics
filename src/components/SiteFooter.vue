<template>
  <footer>
    <div class="hero-image">
      <div class="link-footer">
        <h3 class="title">DC COMICS</h3>
        <a href="">Characters</a>
        <br />
        <a href="">Comics</a>
        <br />
        <a href="">Movies</a>
        <br />
        <a href="">TV</a>
        <br />
        <a href="">Games</a>
        <br />
        <a href="">Videos</a>
        <br />
        <a href="">News</a>

        <h3 class="title">SHOP</h3>
        <a href="">Shop DC</a>
        <br />
        <a href="">Shop DC Collectibles</a>
      </div>
      <div class="link-footer">
        <h3 class="title">DC</h3>
        <a href="">Terms Of Use </a>
        <br />
        <a href="">Privacy policy (New)</a>
        <br />
        <a href="">Ad Choices</a>
        <br />
        <a href="">Advertising</a>
        <br />
        <a href="">Jobs</a>
        <br />
        <a href="">Subscriptions</a>
        <br />
        <a href="">Talent Workshops</a>
        <br />
        <a href="">CPSC Certificates</a>
        <br />
        <a href="">Ratings</a>
        <br />
        <a href="">Shop Help</a>
        <br />
        <a href="">Contact Us</a>
      </div>
      <div class="link-footer">
        <h3 class="title">SITES</h3>
        <a href="">DC</a>
        <a href="">MAD Magazine</a>
        <a href="">DC Kids</a>
        <a href="">DC Universe</a>
        <a href="">DC Power Visa</a>
      </div>
      <div class="dc-footer">
        <!-- <img src="../assets/img/dc-logo.png" alt="" /> -->
      </div>
    </div>
    <div class="social">
      <div class="container-sign-up">
        <span class="sign-up">SIGN-UP NOW</span>
      </div>
      <div class="container-social">
        <p class="follow">FOLLOW US</p>
        <img
          src="../assets/img/footer-facebook.png"
          alt=""
          class="img-footer"
        />
        <img src="../assets/img/footer-twitter.png" alt="" class="img-footer" />
        <img src="../assets/img/footer-youtube.png" alt="" class="img-footer" />
        <img
          src="../assets/img/footer-periscope.png"
          alt=""
          class="img-footer"
        />
        <img
          src="../assets/img/footer-pinterest.png"
          alt=""
          class="img-footer"
        />
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "SiteFooter",
};
</script>

<style lang= "scss">
$link-color: #0282f9;
.hero-image {
  height: 400px;
  background-image: url(../assets/img/footer-bg.jpg);

  display: flex;
}
.dc-footer {
  background-image: url(../assets/img/dc-logo.png);
  width: 460px;
  margin-left: 21rem;
  background-repeat: no-repeat;
  object-fit: cover;
  transform: rotate(-30deg);
  background-size: cover;
  height: 460px;
  opacity: 0.4;
}
.link-footer {
  height: 265px;
  width: 150px;
  margin-left: 12rem;
  margin-right: -15rem;
  padding: 50px;

  .title {
    color: white;
  }
  a {
    text-decoration: none;
    color: white;
    filter: brightness(0.5);
  }
}
.social {
  height: 150px;
  background-color: #303030;
  display: flex;
  position: relative;
  .container-sign-up {
    margin-top: 4rem;
    margin-left: 15rem;
    .sign-up {
      border: 2px solid $link-color;
      padding: 10px;
      color: white;
      font-weight: bold;
    }
  }
  .container-social {
    display: flex;
    margin-left: 35rem;
    margin-top: 50px;
    .follow {
      color: $link-color;
      font-weight: bold;
      font-size: 20px;
    }
    .img-footer {
      height: 30px;
      margin-left: 1rem;
      margin-top: 15px;
    }
  }
}
</style>
