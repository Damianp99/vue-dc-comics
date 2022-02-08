<template>
  <div class="bg-gray">
    <div class="container d-flex">
      <button class="btn sign-up">SIGN-UP NOW!</button>
      <div>
        <ul class="d-flex">
          <li class="txt-blue fw-bold">FOLLOW US</li>
          <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
          <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
          <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
          <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
          <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
        </ul>
      </div>
    </div>
    <div class="bg-black"></div>
  </div>
</template>

<script>
export default {
  name: "BottomFooter",
  data() {
    return {
      link: [],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/style.scss";
.sign-up {
  background-color: #303030;
  color: white;
  font-weight: bold;
}
.bg-gray {
  background-color: #303030;
}
</style>