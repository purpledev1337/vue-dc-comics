<template>
  <div id="app">

    <Header/>

    <Jumbotron/>

    <Products/>

    <footer>
      <InfoBanner/>

      <FooterNav/>
      
      <FooterSocial/>
    </footer>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Products from './components/Products.vue'
import InfoBanner from './components/InfoBanner.vue'
import FooterNav from './components/FooterNav.vue'
import FooterSocial from './components/FooterSocial.vue'


export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Products,
    InfoBanner,
    FooterNav,
    FooterSocial
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
// }

.container {
    width: 70%;
    margin: 0 auto;
}
</style>
