<template>
  <Header />
  <Hero />
  <Main />
  <Vue />
  <Footer />
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Main,
    Footer
  },

  data (){
    return {
    }
  }

}
</script>

<style scoped>

</style>
