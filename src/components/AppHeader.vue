<template>
  <header class="container">
    <img src="../assets/img/dc-logo.png" alt="DC Logo" />
    <nav>
      <ul>
        <li
          v-for="(element, index) in headerLinks"
          :key="index"
          :class="{ active: element.active }"
        >
          <a href="">{{ element.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  data: function () {
    return {
      headerLinks: [
        {
          url: "#",
          text: "Characters",
          active: false,
        },
        {
          url: "#",
          text: "Comics",
          active: false,
        },
        {
          url: "#",
          text: "Movies",
          active: false,
        },
        {
          url: "#",
          text: "TV",
          active: false,
        },
        {
          url: "#",
          text: "Games",
          active: false,
        },
        {
          url: "#",
          text: "Collectibles",
          active: false,
        },
        {
          url: "#",
          text: "Videos",
          active: false,
        },
        {
          url: "#",
          text: "Fans",
          active: false,
        },
        {
          url: "#",
          text: "News",
          active: false,
        },
        {
          url: "#",
          text: "Shop",
          active: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  height: 120px;

  img {
    padding: 1rem;
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

    &:hover {
      border-bottom: 5px solid #0282f9;

      a {
        color: #0282f9;
      }
    }
  }
}
</style>
