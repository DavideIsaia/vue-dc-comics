<template>
  <div class="blue-banner">
    <div class="container">
      <ul>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-digital-comics.png" alt=""
          /></a>
          <span>Digital Comics</span>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-merchandise.png" alt=""
          /></a>
          <span>DC Merchandise</span>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-subscriptions.png" alt=""
          /></a>
          <span>Subscription</span>
        </li>
        <li>
          <a href=""
            ><img src="../assets/img/buy-comics-shop-locator.png" alt=""
          /></a>
          <span>Comic Shop Locator</span>
        </li>
        <li>
          <a href=""
            ><img
              class="svg-file"
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
          /></a>
          <span>DC Power Visa</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlueBanner",
};
</script>

<style lang="scss" scoped>
.blue-banner {
  background-color: #0282f9;
  color: white;
  text-align: center;

  img {
    width: 50%;
  }

  .svg-file {
    width: 20%;
  }

  ul {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  li {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 2rem 1rem;
    text-transform: uppercase;
    cursor: pointer;
  }

  span {
    font-size: 0.8rem;
  }
}
</style>
