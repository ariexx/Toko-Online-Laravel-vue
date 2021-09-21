<template>
  <div class="home">
    <header-shayna />
    <hero-carousel />
    <women-carousel />
    <instagram-gallery />
    <logo-partner />
    <footer-shayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/template/HeaderShayna.vue";
import HeroCarousel from "@/components/section/HeroCarousel.vue";
import WomenCarousel from "@/components/section/WomenCarousel.vue";
import InstagramGallery from "@/components/section/InstagramGallery.vue";
import LogoPartner from "../components/section/LogoPartner.vue";
import FooterShayna from "../components/template/FooterShayna.vue";
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroCarousel,
    WomenCarousel,
    InstagramGallery,
    LogoPartner,
    FooterShayna,
  },
};
</script>
