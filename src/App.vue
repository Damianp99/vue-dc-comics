<template>
  <div>
    <Header />
    <Main />
    <Merchandise />
  </div>
</template>

<script>
import Merchandise from "./components/Merchandise.vue";
import Main from "./components/Main.vue";
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Merchandise,
  },
};
</script>

<style lang="scss">
body {
  margin: 0px;
  font-family: "Roboto", sans-serif;
}
</style>
