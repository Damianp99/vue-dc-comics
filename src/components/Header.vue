<template>
  <div>
    <header>
      <div class="container d-flex">
        <ul>
          <li>
            <img src="../assets/img/dc-logo.png" alt="" />
          </li>
        </ul>
        <!-- questa lista andrà poi messa con un v-for -->
        <ul>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
          <li>COMINCS</li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" >
.container {
  margin: 0 auto;
  max-width: 1200px;
}
.d-flex {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
ul {
  list-style-type: none;
  li {
    display: inline;
    padding: 0px 10px;
    font-weight: bold;
  }
}
</style>