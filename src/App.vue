<template>
  <div id="app">
    <AppHeader />
    <img class="jumbo" src="./assets/img/jumbotron.jpg" alt="jumbo" />
    <DcList />
    <BlueBanner />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import BlueBanner from "./components/BlueBanner.vue";
import AppFooter from "./components/AppFooter.vue";
import DcList from "./components/DcList.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    BlueBanner,
    DcList,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";

.jumbo {
  margin-top: 2px;
  width: 100%;
  height: 450px;
  object-fit: cover;
  object-position: top;
}
</style>
