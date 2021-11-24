<template>
  <section>
    <div class="container">
      <div>
        <img src="..\assets\buy-comics-digital-comics.png" alt="Digital Comis">
        <span>Digital Comis</span>
      </div>
      <div>
        <img src="..\assets\buy-comics-merchandise.png" alt="DC Merchandise">
        <span>DC Merchandise</span>
      </div>
      <div>
        <img src="..\assets\buy-comics-shop-locator.png" alt="Subscription">
        <span>Subscription</span>
      </div>
      <div>
        <img src="..\assets\buy-comics-subscriptions.png" alt="Comic Shop Locator">
        <span>Comic Shop Locator</span>
      </div>
      <div>
        <img src="..\assets\buy-dc-power-visa.svg" alt="DC Power Visa">
        <span>DC Power Visa</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'InfoBanner',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section {
  height: 180px;
  background-color: rgb(2,130,249);
  color: white;
    .container {
      height: 100%;
      display: flex;
      justify-content: space-around;
      align-items: center;
        img {
          height: 50px;
          margin: 0 10px;
        }
        span {
          vertical-align: middle;
          text-transform: uppercase;
        }
    }
}
</style>
