<template>
  <div class="blue-banner">
    <div class="container">
      <ul>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-digital-comics.png" alt=""
          /></a>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-merchandise.png" alt=""
          /></a>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-subscriptions.png" alt=""
          /></a>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-shop-locator.png" alt=""
          /></a>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-dc-power-visa.svg" alt=""
          /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.blue-banner {
  height: 150px;
  background-color: #0282f9;
  color: white;
  text-align: center;
}

img {
  width: 50%;
}

ul {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
}

li {
  display: inline-block;
  margin: 0 1rem;
  text-transform: uppercase;
  line-height: 120px;
  border-bottom: 5px solid transparent;
  cursor: pointer;
}
</style>
