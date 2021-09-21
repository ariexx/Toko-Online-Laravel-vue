<template>
  <div class="cart">
    <header-shayna />
    <breadcrumb-cart />
    <Details />
    <footer-shayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/template/HeaderShayna";
import FooterShayna from "@/components/template/FooterShayna";
import BreadcrumbCart from "@/components/cart/BreadcrumbCart.vue";
import Details from "@/components/cart/Details";
export default {
  name: "Cart",
  components: {
    HeaderShayna,
    FooterShayna,
    BreadcrumbCart,
    Details,
  },
};
</script>

<style></style>
