<template>
  <div class="container">
    <Header />
    <background-image />
    <introduce />
    <product />
    <service />
    <information />
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/header/Navbar';
import BackgroundImage from '~/components/background/BackgroundImage';
import Introduce from '~/components/introduce/Introduce';
import Product from '~/components/product/Product';
import Service from '~/components/service/Service';
import Information from '~/components/information/Information';
import Footer from '~/components/footer/Footer';

export default {
  components: {
    Header,
    BackgroundImage,
    Introduce,
    Product,
    Service,
    Information,
    Footer,
  },
};
</script>

<style>
.container {
  background-color: #fff;
}
</style>
