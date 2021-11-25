<template>
  <section>
    <div class="container">
      <div class="btn">
        SIGN-UP NOW!
      </div>
      <div>
        <span>FOLLOW US</span>
        <img src="..\assets\footer-facebook.png" alt="">
        <img src="..\assets\footer-twitter.png" alt="">
        <img src="..\assets\footer-youtube.png" alt="">
        <img src="..\assets\footer-pinterest.png" alt="">
        <img src="..\assets\footer-periscope.png" alt="">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FooterSocial'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section {
  height: 120px;
  background-color: rgb(48,48,48);
    .container {
      height: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
}

.btn {
  display: inline-block;
  color: white;
  padding: 15px;
  border: 1px solid rgb(2,130,249);
}

span {
  color: rgb(2,130,249);
  font-size: 2em;
}

img {
  margin: 0 15px;
}
</style>
