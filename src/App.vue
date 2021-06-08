<template>
  <div id="app">
    <Nav />
    <Jumbotron />
    <ContentOne />
    <ContentBar />
    <Footer />
    <Social />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Jumbotron from './components/Jumbotron.vue'
import ContentOne from './components/ContentOne.vue'
import ContentBar from './components/ContentBar.vue'
import Footer from './components/Footer.vue'
import Social from './components/Social.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Jumbotron,
    ContentOne,
    ContentBar,
    Footer,
    Social
  },
}
</script>

<style lang="scss">
@import "./style/general.scss";

</style>