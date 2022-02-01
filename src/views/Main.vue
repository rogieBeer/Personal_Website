<template>
  <v-app>
      <Navbar/>
      <v-main>
        <Hero/>
        <Projects/>
        <About/>
      </v-main>
      <Footer/>
  </v-app>
</template>

<script>
  import Navbar from '@/components/navbar/Navbar.vue'
  import Hero from '@/components/hero/Hero.vue'
  import Projects from '@/components/primaryContent/projects/Project.vue'
  import About from '@/components/primaryContent/about/About.vue'
  import Footer from '@/components/footer/Footer.vue'
  export default {
    name: 'Home',

    components: {
      Navbar,
      Hero,
      Projects,
      About,
      Footer
    },
  }
</script>
