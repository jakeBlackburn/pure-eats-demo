<template>
  <div class="app-container">
    <Header />
    <Menu />
    <Buttons />
    <About />
    <Gallery />
    <Map />
    <Footer />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Menu from './components/Menu.vue'
  import Buttons from './components/Buttons.vue'    
  import About from './components/About.vue'
  import Gallery from './components/Gallery.vue'
  import Map from './components/Map.vue'
  import Footer from './components/Footer.vue'


  export default {
    name: 'App',
    components: {
      Header,
      Menu,
      Buttons,
      About,
      Gallery,
      Map,
      Footer
    }
  }
</script>

<style>
body {
  background-color: white;
  margin: 0;
  font-family: 'Bebas Neue';
}
</style>
