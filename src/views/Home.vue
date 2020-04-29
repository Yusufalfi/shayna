<template>
  <div class="home">
    <Header />
    <HeroCarousel />
    <ProductCarousel />
    <instagram />
    <Sponsor />
    <Footer />
    

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue';
import HeroCarousel from '@/components/HeroCarousel.vue';
import ProductCarousel from '@/components/ProductCarousel.vue';
import instagram from '@/components/instagram.vue';
import Sponsor from '@/components/Sponsor.vue';
import Footer from '@/components/Footer.vue';






export default {
  name: 'Home',
  components: {
   Header,
   HeroCarousel,
   ProductCarousel,
   instagram,
   Sponsor,
   Footer,
   
  }
};
</script>
