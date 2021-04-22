<template>
<div class="home">
      <HeaderShayna />
      <HeroShayna />
      <WomenShayna />
      <InstaShayna />
      <PartnerShayna />
      <FooterShayna />
</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna";
import HeroShayna from "@/components/HeroShayna";
import WomenShayna from "@/components/WomenShayna";
import InstaShayna from "@/components/InstaShayna";
import PartnerShayna from "@/components/PartnerShayna";
import FooterShayna from "@/components/FooterShayna";


export default {
      name: "Home",
      components: {
            HeaderShayna,
            HeroShayna,
            WomenShayna,
            InstaShayna,
            PartnerShayna,
            FooterShayna,
      }
};
</script>
