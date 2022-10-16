<template>
  <div class="Homeview">
    <HeaderHome />
    <BreadCrumb />
    <ViewProduct />
    <RelatedProducts />
    <FooterS />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHome from '@/components/HeaderHome.vue';
import ViewProduct from '@/components/ViewProduct.vue';
import FooterS from '@/components/FooterS.vue';
import RelatedProducts from '@/components/RelatedProducts.vue';
import BreadCrumb from '@/components/BreadCrumb.vue';

export default {
  name: 'ProductView',
  components: {
    HeaderHome,
    ViewProduct,
    RelatedProducts,
    FooterS,
    BreadCrumb,
  },
};
</script>
