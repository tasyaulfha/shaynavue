<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna  />
    <WomenShayna />
    <InstaShayna />
    <PartnerShayna />
    <Footer />
  </div>
</template>

<script>
import HeaderShayna from "../components/HeaderShayna.vue";
//import carousel from "vue-owl-carousel";
import HeroShayna from "../components/HeroShayna.vue"
import WomenShayna from "../components/WomenShayna.vue"
import InstaShayna from "../components/InstaShayna.vue"
import PartnerShayna from "../components/PartnerShayna.vue"
import Footer from "../components/Footer.vue"

export default {
  name: "Home",
  components: {
    HeaderShayna,
 //   carousel,
    HeroShayna,
    WomenShayna,
    InstaShayna,
    PartnerShayna,
    Footer
  },
};
</script>
