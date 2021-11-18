<template>
  <main id="main">
    <About />
    <Services />
    <Team />
    <!-- <Client /> -->
    <Contact />
  </main>
</template>

<script>
import About from './pages/About.vue';
import Services from './pages/Services.vue';
import Team from './pages/Team.vue';
// import Client from './pages/Client.vue';
import Contact from './pages/Contact.vue';

export default {
  components: {
    About,
    Services,
    Team,
    // Client,
    Contact
  }
}
</script>

<style scoped>

</style>