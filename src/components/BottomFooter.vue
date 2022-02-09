<template>
  <div>
    <div class="bg-gray">
      <div class="container d-flex">
        <button class="btn sign-up">SIGN-UP NOW!</button>
        <div>
          <ul class="d-flex">
            <li class="txt-blue fw-bold">FOLLOW US</li>
            <li v-for="image in images" :key="image.url">
              <img
                :src="require(`../assets/img/${image.url}`)"
                :alt="image.alt"
              />
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
          url: "footer-facebook.png",
          alt: "Facebook",
        },
        {
          url: "footer-periscope.png",
          alt: "Periscope",
        },
        {
          url: "footer-pinterest.png",
          alt: "Pinterest",
        },
        {
          url: "footer-twitter.png",
          alt: "Twitter",
        },
        {
          url: "footer-youtube.png",
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
  cursor: pointer;
}
.bg-gray {
  background-color: #303030;
}
</style>