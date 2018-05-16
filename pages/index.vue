<template>
  <div class="container">
    <Header />
    <background-image />
    <introduce />
  </div>
</template>

<script>
import Header from '~/components/header/Navbar';
import BackgroundImage from '~/components/background/BackgroundImage';
import Introduce from '~/components/introduce/Introduce';

export default {
  components: {
    Header,
    BackgroundImage,
    Introduce,
  },
};
</script>

<style>
.container {
  background-color: #fff;
}
</style>
