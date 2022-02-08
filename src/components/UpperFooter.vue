<template>
  <div>
    <section class="jumbo-upperfooter">
      <div class="container">
        <div class="d-flex">
          <div class="w-30 flex-list">
            <ul>
              <li><h3>DC COMICS</h3></li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
            </ul>
            <ul>
              <li><h3>SHOP</h3></li>
              <li>Characters</li>
              <li>Characters</li>
            </ul>
            <ul>
              <li><h3>DC</h3></li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
            </ul>
            <ul>
              <li><h3>SITES</h3></li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
              <li>Characters</li>
            </ul>
          </div>
          <div class="logo-bg"></div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../assets/sass/style.scss";

.w-30 {
  width: 40%;
}

.logo-bg {
  background-image: url(../assets/img/dc-logo-bg.png);
  background-size: cover;
  background-repeat: no-repeat;
  height: 400px;
  width: 500px;
}
.flex-list {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  flex-direction: column;
  flex-wrap: wrap;
  align-items: flex-start;
  height: 400px;
}

ul {
  padding: 0px;
}
li {
  display: block;
  padding: 0px;
  font-weight: normal;
  font-size: 14px;
  color: gray;
  h3 {
    color: white;
  }
}
.jumbo-upperfooter {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  height: 400px;
  background-size: cover;
}
</style>