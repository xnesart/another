<template>
  <div class="v-item">
    <div class="photo__item">
      <div class="photo__item-info">
        <img class="photo__item-avatar" src="../assets/images/avatar.jpg" alt="Avatar" />
        <h6 class="photo__item-name">{{ product_data.name }}</h6>
        <a class="photo__item-sublink" href="https://www.instagram.com/jason_mowry_photos/">@jason_mowry_photo</a>
      </div>
      <div class="photo__item-img">
        <img class="photo__item-thumb"  v-bind:src=" require('../assets/images/' + product_data.image) " alt="photo" />
      </div>
      <span class="photo__item-looks">{{ product_data.view }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "v-item",
    props: {
    product_data: {
      type: Object,
      default(){
        return {}
      }
    }
  },
  data() {
    return{}
  },
  computed: {}
};
</script>

<style></style>
