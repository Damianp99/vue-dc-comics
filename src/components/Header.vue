<template>
  <div>
    <div class="bg-black"></div>
    <header>
      <div class="container d-flex">
        <img src="../assets/img/dc-logo.png" alt="" />

        <!-- questa lista andrà poi messa con un v-for -->
        <ul class="menu-list">
          <li v-for="link in links" :key="link.text">
            {{ link.text }}
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "CHARACTERS",
        },
        {
          text: "COMICS",
        },
        {
          text: "MOVIES",
        },
        {
          text: "TV",
        },
        {
          text: "GAMES",
        },
        {
          text: "COLLECTIBLES",
        },
        {
          text: "VIDEOS",
        },
        {
          text: "FANS",
        },
        {
          text: "NEWS",
        },
        {
          text: "SHOP",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/style.scss";
.menu-list {
  font-size: 12px;
  color: #1c1c1c;
}
li {
  cursor: pointer;
}

img {
  padding: 10px;
}
</style>