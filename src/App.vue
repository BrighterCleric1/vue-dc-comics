<template>
  <div id="app">
    <Header />
    <Main />
    <PreFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import PreFooter from "./components/PreFooter.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    PreFooter,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./style/app.scss";
</style>
