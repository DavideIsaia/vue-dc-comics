<template>
  <footer>
    <div class="container">
      <div class="link-list">
        <div class="link-list__col">
          <h3>Dc Comics</h3>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">Tv</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
          </ul>
          <h3>Shop</h3>
          <ul>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="link-list__col">
          <h3>DC</h3>
          <ul>
            <li><a href="">Terms Of Use</a></li>
            <li><a href="">Privacy Policy (New)</a></li>
            <li><a href="">Ad CHoices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshop</a></li>
            <li><a href="">CPSC Certifications</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">Contact Us</a></li>
          </ul>
        </div>
        <div class="link-list__col">
          <h3>Sites</h3>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <img src="../assets/img/dc-logo-bg.png" alt="dclogo" />
    </div>
    <div class="footer-bottom container"></div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;

  .container {
    display: flex;
    justify-content: space-between;

    .link-list {
      display: flex;

      &__col {
        margin-right: 3rem;
      }
    }

    h3 {
      text-transform: uppercase;
      color: white;
      padding: 1rem 0;
    }

    li {
      color: grey;

      &:hover {
        color: white;
        cursor: pointer;
      }
    }

    img {
      width: 350px;
    }
  }
}
</style>
