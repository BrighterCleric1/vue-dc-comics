<template>
  <div class="all">
    <div class="jumbo">yo</div>
    <div class="main-bg">
      <div class="container">
        <div class="current">CURRENT SERIES</div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Main",
};
</script>


<style lang="scss" scoped>
@import "../style/colors.scss";
@import "../style/fonts.scss";
.main-bg {
  font-family: "Open Sans", sans-serif;
  height: 200px;
  background-color: #002;
  .container {
    position: relative;
    .current {
      position: absolute;
      color: white;
      height: 40px;
      top: -20px;
      background-color: $blue;
      padding: 10px;
    }
  }
}
.jumbo {
  height: 250px;
  background-image: url("../assets/jumbotron.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}
</style>