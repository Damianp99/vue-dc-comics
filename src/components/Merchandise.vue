<template>
  <div class="bg-blue">
    <section id="merchandise-links" class="container">
      <div>
        <!--Da riempire con v-for-->
        <ul>
          <li v-for="link in links" :key="link.text">
            <a href="#"> {{ link.text }}</a>
          </li>
        </ul>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Merchandise",
  data() {
    return {
      links: [
        {
          text: "DIGITAL COMICS",
          img: "../assets/img/buy-comics-digital-comics.png",
        },
        {
          text: "DC MERCHANDISE",
          img: "../assets/img/buy-comics-digital-comics.png",
        },
        {
          text: "SUBSCRIPTION",
          img: "../assets/img/buy-comics-subscriptions.png",
        },
        {
          text: "COMIC SHOP LOCATOR",
          img: "../assets/img/buy-comics-shop-locator.png",
        },
        {
          text: "DC POWER VISA",
          img: "../assets/img/buy-dc-power-visa.svg",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/style.scss";
.bg-blue {
  background-color: #0282f9;
  height: 150px;
  display: flex;
  align-items: center;
}
.merch-img-size {
  height: 50px;
  padding: 0 5px;
}
</style>