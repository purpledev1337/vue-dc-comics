<template>
    <div class="product_card">
      <img :src="img" />
      <div class="product_name">
          {{ seriesName }}
      </div>
    </div>
</template>

<script>
export default {
  name: 'ProductCard',
  props: {
      img: String,
      seriesName: String,
      price: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.product_card {
    width: calc((100% / 6) - 20px);
    margin: 0 10px;
    margin-bottom: 40px;
}

img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    object-position: top;
}

.product_name {
    text-transform: uppercase;
    margin-top: 15px;
}
</style>
