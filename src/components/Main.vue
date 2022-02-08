<template>
  <div>
    <main class="bg-black">
      <div class="container txt-white-important">
        <h2>Content goes here</h2>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss" >
main {
  margin: 0px;
}
.bg-black {
  background-color: #1c1c1c;
  height: 150px;
}
.txt-white-important {
  color: white;
  font-weight: bold;
  //   line height da togliere e fare una classe generica
  line-height: 150px;
}
</style>