<template>
  <header>
    <div class="container">
      <div class="logo-img">
        <img src="../assets/dc-logo.png" alt="logo" />
      </div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>



<script>
export default {
  name: "Header",
};
</script>


<style lang="scss" scoped>
@import "../style/colors.scss";
@import "../style/fonts.scss";
header {
  height: 115px;
  .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    .logo-img {
      transform: scale(90%);
    }
    ul {
      font-family: "Open Sans", sans-serif;
      align-items: center;
      list-style: none;
      display: flex;
      height: 115px;
      color: $h-color;
      li {
        font-size: 15px;
        line-height: 115px;
        height: 100%;
        margin: 0 15px;
        font-weight: bold;
        &:hover {
          cursor: pointer;
          color: $blue;
          border-bottom: 6px solid $blue;
        }
      }
    }
  }
}
</style>