<template>
  <div id="app">
    <AppHeader />
    <main>Content goes here</main>
    <BlueBanner />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import BlueBanner from "./components/BlueBanner.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    BlueBanner,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";

main {
  margin-top: 2px;
  height: 150px;
  background-color: #1c1c1c;
  color: white;
  text-align: center;
  line-height: 150px;
}
</style>
