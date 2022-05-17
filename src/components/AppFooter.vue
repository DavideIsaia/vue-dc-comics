<template>
  <footer>
    <div class="footer-top">
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
    </div>
    <div class="footer-bottom">
      <div class="container">
        <button>sign-up now!</button>
        <div class="social-links">
          <h2>Follow Us</h2>
          <ul>
            <li>
              <a href=""
                ><img src="../assets/img/footer-facebook.png" alt=""
              /></a>
            </li>
            <li>
              <a href=""
                ><img src="../assets/img/footer-twitter.png" alt=""
              /></a>
            </li>
            <li>
              <a href=""
                ><img src="../assets/img/footer-youtube.png" alt=""
              /></a>
            </li>
            <li>
              <a href=""
                ><img src="../assets/img/footer-periscope.png" alt=""
              /></a>
            </li>
            <li>
              <a href=""
                ><img src="../assets/img/footer-pinterest.png" alt=""
              /></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.footer-top {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;

  .link-list {
    display: flex;

    &__col {
      margin-right: 3rem;
    }
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

.footer-bottom {
  background-color: #303030;
  height: 150px;

  .social-links,
  ul {
    display: flex;
    justify-content: space-between;
    align-items: center;

    li {
      margin: 3rem 0.5rem;
    }
  }
}
</style>
