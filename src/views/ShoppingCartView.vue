<template>
  <div class="Homeview">
    <HeaderHome />
    <BreadCrumb />
    <ViewCart />
    <FooterS />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHome from '@/components/HeaderHome.vue';
import ViewCart from '@/components/ViewCart.vue';
import BreadCrumb from '@/components/BreadCrumb.vue';
import FooterS from '@/components/FooterS.vue';

export default {
  name: 'ProductView',
  components: {
    HeaderHome,
    ViewCart,
    BreadCrumb,
    FooterS,
  },
};
</script>
