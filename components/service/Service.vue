<template>
  <div class="service-container">
    <h2>Build products, apps and services</h2>
    <p>DigitalToken is the professional choice for designers,
      developers and teams.</p>
    <div class="item-container">
      <service-item
        v-for="(item,id) in service"
        :key="id"
        :image="item.image"
        :title="item.title"
        :description="item.description"
      />
    </div>
    <h4><a href="#">Learn more about why DigitalToken fits in your company →</a></h4>
  </div>
</template>

<script>
import ServiceItem from './ServiceItem';
import Service from '../../constant/service';

export default {
  components: {
    ServiceItem,
  },
  computed: {
    service() {
      return Service;
    },
  },
};
</script>


<style>
.service-container {
  width: 70%;
  margin-top: 20px;
  margin-left: 15%;
  display: flex;
  flex-direction: column;
  align-items: center;
  border-bottom: 1px solid #bfbdbd;
}
.service-container h2 {
  color: #535353;
  margin-top: 15px;
}
.service-container p {
  color: #535353;
  margin-top: 10px;
}
.service-container .item-container {
  width: 100%;
  display: flex;
}
.service-container h4 {
  margin-bottom: 50px;
}
.service-container h4 a {
  text-decoration: none;
  color: #0080ff;
}
</style>
