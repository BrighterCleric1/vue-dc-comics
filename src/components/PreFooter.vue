<template>
  <div class="buttons-pref">
    <div class="container">
      <ul>
        <li>
          <div class="button-img">
            <img src="../assets/buy-comics-digital-comics.png" alt="" />
          </div>
          <span class="button-link"><a href="#">Digital Comics</a></span>
        </li>
        <li>
          <div class="button-img">
            <img src="../assets/buy-comics-merchandise.png" alt="" />
          </div>
          <span class="button-link"><a href="#">Merchandise</a></span>
        </li>
        <li>
          <div class="button-img">
            <img src="../assets/buy-comics-shop-locator.png" alt="" />
          </div>
          <span class="button-link"><a href="#">Shop Locator</a></span>
        </li>
        <li>
          <div class="button-img">
            <img src="../assets/buy-comics-subscriptions.png" alt="" />
          </div>
          <span class="button-link"><a href="#">Subscriptions</a></span>
        </li>
        <li>
          <div class="button-img">
            <img src="../assets/buy-dc-power-visa.svg" alt="" />
          </div>
          <span class="button-link"><a href="#">DC Power Visa</a></span>
        </li>
      </ul>
    </div>
  </div>
</template>


<script>
export default {
  name: "PreFooter",
};
</script>


<style lang="scss" scoped>
@import "../style/colors.scss";
@import "../style/fonts.scss";
.buttons-pref {
  height: 150px;
  background-color: $blue;
  .container {
    ul {
      font-family: "Open Sans", sans-serif;
      list-style: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
      li {
        line-height: 150px;
        display: flex;
        align-items: center;
        .button-link {
          margin: 0 10px;
          a {
            text-decoration: none;
            color: #fff;
            &:hover {
              text-decoration: underline;
            }
          }
        }
        .button-img {
          display: flex;
          align-items: center;
        }
        img {
          height: 55px;
        }
      }
    }
  }
}
</style>