<template>
  <div class="home">
    <HeaderHilya />
    <HeroHilya />
    <ItemBanner />
    <InstaHilya />
    <LogoPartner />
    <FooterHilya />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import HeaderHilya from "@/components/HeaderHilya.vue";
import HeroHilya from "@/components/HeroHilya.vue";
import ItemBanner from "@/components/ItemBanner.vue";
import InstaHilya from "@/components/InstaHilya.vue";
import LogoPartner from "@/components/LogoPartner.vue";
import FooterHilya from "@/components/FooterHilya.vue";

export default {
  name: "Home",
  components: {
    HeaderHilya,
    HeroHilya,
    ItemBanner,
    InstaHilya,
    LogoPartner,
    FooterHilya,
  },
};
</script>
