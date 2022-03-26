<template>

  <div> 
    <TopBar />
    <HeroSlideShow />
    <Chef />
    <BrandGallery />
    <Showcase />
    <Catering />
    <MelShowcase />
    <Beans />
    <Footer />
   </div>
 
</template>




<script>
  import TopBar from './components/TopBar.vue'
  import HeroSlideShow from './components/HeroSlideShow.vue'
  import Chef from './components/Chef.vue'
  import BrandGallery from './components/BrandGallery.vue'
  import Showcase from './components/Showcase.vue'
  import Catering from './components/Catering.vue'
  import MelShowcase from './components/MelShowcase.vue'
  import Beans from './components/BeansSection.vue'
  import Footer from './components/Footer.vue'

  export default {
    name: 'App',
    components: {
      TopBar,
      HeroSlideShow,
      Chef,
      BrandGallery,
      Showcase,
      Catering,
      MelShowcase,
      Beans,
      Footer

    }
  }

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
