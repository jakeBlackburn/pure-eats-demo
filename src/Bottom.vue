<template>
    <div class="bottom-container">
        <About /> 
        <Gallery />
        <Footer />
    </div>
</template>

<script>
    import About from './components/About.vue'
    import Gallery from './components/Gallery.vue'
    import Footer from './components/Footer.vue'



    export default {
        name: 'Bottom',
        components: {
            About, 
            Gallery,
            Footer
        }
    }
</script>