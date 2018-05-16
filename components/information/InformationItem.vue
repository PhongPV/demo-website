<template>
  <div class="item-info">
    <img
      :src="image"
      alt="img-information">
    <h3>{{title}}</h3>
    <p>{{description}}</p>
    <div class="button-buying">
      <a href="#">Buying</a>
    </div>
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
.item-info {
  width: 30%;
  margin: 0 3%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px 10px;
}
.item-info h3 {
  padding: 15px 0;
  color: #535353;
}
.item-info p {
  text-align: center;
  padding: 20px 0;
  color: #535353;
}
.item-info .button-buying {
  width: 150px;
  height: 40px;
  background-color: #0080ff;
  display: flex;
  align-items: center;
  justify-content: center;
}
.item-info .button-buying a {
  text-decoration: none;
  color: #fff;
}
</style>
