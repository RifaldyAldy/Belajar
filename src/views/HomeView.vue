<template>
  <div class="Homeview">
    <HeaderHome />
    <HeroSHome />
    <BannerHome />
    <Instagram />
    <NamaBrands />
    <FooterS />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHome from '@/components/HeaderHome.vue';
import HeroSHome from '@/components/HeroSHome.vue';
import BannerHome from '@/components/BannerHome.vue';
import Instagram from '@/components/InstaToko.vue';
import NamaBrands from '@/components/NamaBrands.vue';
import FooterS from '@/components/FooterS.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderHome,
    HeroSHome,
    BannerHome,
    NamaBrands,
    Instagram,
    FooterS,
  },
};
</script>
