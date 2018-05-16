<template>
  <div class="info-container">
    <h2>More Information</h2>
    <div class="item-container">
      <information-item
        v-for="(item, id) in information"
        :key="id"
        :image="item.image"
        :title="item.title"
        :description="item.description"
      />
    </div>
  </div>
</template>

<script>
import InformationItem from './InformationItem';
import information from '../../constant/information';

export default {
  components: {
    InformationItem,
  },
  computed: {
    information() {
      return information;
    },
  },
};
</script>

<style>
.info-container {
  width: 70%;
  margin-left: 15%;
  margin-top: 50px;
  margin-bottom: 50px;
}
.info-container h2 {
  color: #535353;
  margin-top: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.info-container .item-container {
  display: flex;
  margin-top: 30px;
}
</style>
