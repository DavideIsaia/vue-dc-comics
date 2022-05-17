<template>
  <div id="app">
    <AppHeader />
    <main>Content goes here</main>
    <div class="blue-banner">Bonus</div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
main {
  height: 100px;
  background-color: #1c1c1c;
  color: white;
  text-align: center;
  line-height: 100px;
}

.blue-banner {
  height: 300px;
  background-color: #0282f9;
  color: white;
  text-align: center;
  line-height: 100px;
}
</style>
