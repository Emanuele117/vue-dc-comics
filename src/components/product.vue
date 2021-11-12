<template>
  <div class="cards">
    <img :src="image" alt="" />
    <h3>{{ titolo }}</h3>
    <p>{{ price }}</p>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    titolo: String,
    price: String,
  },
};
</script>

<style>
</style>