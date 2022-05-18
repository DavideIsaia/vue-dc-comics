<template>
  <div class="comics">
    <img :src="comicsObj.thumb" alt="" />
    <h5>{{ comicsObj.type }}</h5>
    <h4>{{ comicsObj.series }}</h4>
    <h6>{{ comicsObj.price }}</h6>
  </div>
</template>

<script>
export default {
  name: "AppComics",
  props: {
    comicsObj: Object,
  },
};
</script>

<style lang="scss" scoped>
.comics {
  width: calc(100% / 6 - 12px);
  background-color: white;
  padding: 2rem 0.5rem;
  cursor: pointer;

  &:hover {
    filter: brightness(0.8);
  }
}
</style>
