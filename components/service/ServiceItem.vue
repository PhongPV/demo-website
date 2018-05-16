<template>
  <div class="service-item">
    <img
      :src="image"
      alt="img-service"/>
    <h3><a href="#">{{title}}</a></h3>
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
.service-item {
  width: 25%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 15px 10px;
}
.service-item h3 {
  padding: 15px 0;
}
.service-item h3 a {
  text-decoration: none;
  color: #535353;
}
.service-item p {
  text-align: center;
  padding: 20px 0;
}
</style>
