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
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
          active: false,
        },
        {
          url: "#",
          text: "Link",
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
  justify-content: space-between;

  li {
    display: inline-block;
  }
}
</style>
