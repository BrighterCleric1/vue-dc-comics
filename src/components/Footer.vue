<template>
  <div class="footer-cont">
    <div class="first-f">
      <div class="container">
        <div class="row">
          <div class="col">
            <ul>
              <li>DC COMICS</li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
            </ul>
            <ul>
              <li>SHOP</li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>DC</li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>SITES</li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
              <li><a href="#">ciao</a></li>
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
    <div class="second-f"></div>
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
  height: 110px;
  background-color: #303030;
}
</style>