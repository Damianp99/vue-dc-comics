<template>
  <div>
    <div class="bg-gray">
      <div class="container d-flex">
        <button class="btn sign-up">SIGN-UP NOW!</button>
        <div>
          <ul class="d-flex">
            <li class="txt-blue fw-bold">FOLLOW US</li>
            <li v-for="image in images" :key="image.url">
              <img :src="image.url" :alt="image.alt" />
            </li>
          </ul>
        </div>
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
      images: [
        {
          url: "../assets/img/footer-facebook.png",
          alt: "Facebook",
        },
        {
          url: "../assets/img/footer-periscope.png",
          alt: "Periscope",
        },
        {
          url: "../assets/img/footer-pinterest.png",
          alt: "Pinterest",
        },
        {
          url: "../assets/img/footer-twitter.png",
          alt: "Twitter",
        },
        {
          url: "../assets/img/footer-youtube.png",
          alt: "Youtube",
        },
      ],
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