<template>
  <div id="app">
    <Header />
    <Main />
    <BlueBar />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import BlueBar from './components/BlueBar.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    BlueBar,
    Footer
  }
}
</script>

<style lang="scss">
@import "./style/app.scss"
</style>
