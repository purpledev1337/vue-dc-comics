<template>
  <div id="app">

    <Header/>

    <Main/>

    <footer>
      <InfoBanner/>

      <FooterNav/>
      
      <FooterSocial/>
    </footer>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import InfoBanner from './components/InfoBanner.vue'
import FooterNav from './components/FooterNav.vue'
import FooterSocial from './components/FooterSocial.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
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
    width: 80%;
    margin: 0 auto;
}
</style>
