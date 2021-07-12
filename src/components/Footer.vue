<template>
  <div class="footer-cont">
    <div class="first-f">
      <div class="container">
        <div class="row">
          <div class="col">
            <ul>
              <li>DC COMICS</li>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <ul>
              <li>SHOP</li>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop Dc Collectibles</a></li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>DC</li>
              <li><a href="#">Termy Of Use</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subrscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>SITES</li>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazines</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
          <div class="col col-logo">
            <div class="img-footer">
              <img src="../assets/dc-logo-bg.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="second-f">
      <div class="container">
        <div class="row">
          <div class="col">
            <div class="button-sign">
              <button class="signup">SIGN-UP NOW!</button>
            </div>
          </div>
          <div class="col">
            <ul class="social">
              <li>FOLLOW US</li>
              <li>
                <img src="../assets/footer-facebook.png" alt="" />
              </li>
              <li>
                <img src="../assets/footer-periscope.png" alt="" />
              </li>
              <li>
                <img src="../assets/footer-twitter.png" alt="" />
              </li>
              <li>
                <img src="../assets/footer-pinterest.png" alt="" />
              </li>
              <li>
                <img src="../assets/footer-youtube.png" alt="" />
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Footer",
};
</script>


<style lang="scss" scoped>
@import "../style/colors.scss";
@import "../style/fonts.scss";

.first-f {
  font-family: "Open Sans", sans-serif;
  height: 385px;
  background-image: url("../assets/footer-bg.jpg");
  overflow: hidden;
  .row {
    display: flex;
    justify-content: space-between;
    .col-logo {
      height: 385px;
      .img-footer {
        height: 100%;
        img {
          height: 100%;
          transform: scale(110%);
        }
      }
    }
  }
  .col {
    margin-right: 100px;
    ul {
      padding-top: 35px;
      li {
        &:first-child {
          color: white;
          font-weight: bold;
          margin-bottom: 12px;
        }
        a {
          color: #bbb;
          text-decoration: none;
          font-size: 12px;
        }
      }
    }
  }
}
.second-f {
  font-family: "Open Sans", sans-serif;
  height: 110px;
  background-color: #303030;
  .row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    line-height: 110px;
    .social {
      display: flex;
      align-items: center;
      li {
        display: flex;
        align-items: center;
        margin: 0 10px;
        &:hover {
          cursor: pointer;
        }
        &:first-child {
          color: $blue;
          font-weight: bold;
        }
      }
    }
  }
}
.signup {
  font-family: "Open Sans", sans-serif;
  padding: 10px;
  border: 4px solid $blue;
  color: #fff;
  background: none;
}
</style>