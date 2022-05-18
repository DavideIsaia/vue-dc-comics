<template>
  <div class="comics">
    <img :src="comicsObj.thumb" alt="" />
    <h4>{{ comicsObj.series }}</h4>
  </div>
</template>

<script>
export default {
  name: "AppComics",
  // Passare i valori come un'oggetto unico in due modi: object notation oppure array di stringhe
  props: {
    comicsObj: Object,
  },
};
</script>

<style lang="scss" scoped>
.comics {
  width: calc(100% / 6 - 12px);
  background-color: white;
  padding: 1rem 0.5rem;
  margin: 2px;
  h4 {
    font-size: 0.8rem;
    text-align: center;
  }
}
</style>
