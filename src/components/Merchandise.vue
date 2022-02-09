<template>
  <div class="bg-blue">
    <section id="merchandise-links" class="container">
      <div>
        <ul>
          <li v-for="link in links" :key="link.text">
            <img
              class="merch-img-size"
              :src="require(`../assets/img/${link.img}`)"
              alt=""
            />
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
          img: "buy-comics-digital-comics.png",
        },
        {
          text: "DC MERCHANDISE",
          img: "buy-comics-merchandise.png",
        },
        {
          text: "SUBSCRIPTION",
          img: "buy-comics-subscriptions.png",
        },
        {
          text: "COMIC SHOP LOCATOR",
          img: "buy-comics-shop-locator.png",
        },
        {
          text: "DC POWER VISA",
          img: "buy-dc-power-visa.svg",
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
  height: 40px;
  padding: 0 5px;
}
li a {
  font-size: 16px;
  font-weight: normal;
}
</style>