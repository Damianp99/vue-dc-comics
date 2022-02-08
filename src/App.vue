<template>
  <div>
    <Header />
    <Main />
    <Merchandise />
    <UpperFooter />
    <BottomFooter />
  </div>
</template>

<script>
import BottomFooter from "./components/BottomFooter.vue";
import UpperFooter from "./components/UpperFooter.vue";
import Merchandise from "./components/Merchandise.vue";
import Main from "./components/Main.vue";
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Merchandise,
    UpperFooter,
    BottomFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
body {
  min-height: 100vh;
  margin: 0px;
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
}
</style>
