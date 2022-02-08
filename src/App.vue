<template>
  <div>
    <Header />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
body {
  font-family: "Roboto", sans-serif;
}
</style>
