<template>
  <div class="product-item">
    <img
      :src="image"
      alt="img-business"
      class="image"/>
    <h2 class="title"><a href="#">{{title}}</a></h2>
    <p>{{description}}</p>
  </div>
</template>
<script>
export default {
  props: {
    image: {
      type: String,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
};
</script>
<style>
.product-item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.product-item .image {
  width: 40%;
  height: 150px;
}
.product-item .title {
  margin-top: 20px;
}
.product-item .title a {
  text-decoration: none;
  color: #535353;
}
.product-item p {
  margin: 20px 10%;
  color: #535353;
}
</style>
