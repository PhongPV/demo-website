<template>
  <div class="product-container">
    <div
      v-for="(item, id) in product"
      :key="id">
      <product-item
        :image="item.image"
        :title="item.title"
        :description="item.description"/>
    </div>
  </div>
</template>

<script>
import ProductItem from './ProductItem';
import product from '../../constant/product';

export default {
  components: {
    ProductItem,
  },
  computed: {
    product() {
      return product;
    },
  },
};
</script>

<style>
.product-container {
  width: 70%;
  margin-left: 15%;
  display: flex;
  margin-top: 50px;
}
</style>
