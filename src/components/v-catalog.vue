<template>
  <div class="v-catalog">
    <v-item v-for="product in products" :key="product.name" v-bind:product_data="product"> </v-item>
  </div>
</template>

<script>
import vItem from "./v-item";
export default {
  name: "v-catalog",
  components: {
    vItem,
  },
  props: {},
  data() {
    return {
      products: [
        {
          name: "Photo 1",
          image: "type1.jpg",
          view: 100,
        },
        {
          name: "Photo 2",
          image: "type2.jpg",
          view: 2324320,
        },
        {
          name: "Photo 3",
          image: "type3.jpg",
          view: 332340,
        },
        {
          name: "Photo 4",
          image: "type4.jpg",
          view: 300,
        },
        {
          name: "Photo 5",
          image: "type5.jpg",
          view: 1200,
        },
        {
          name: "Photo 6",
          image: "type6.jpg",
          view: 300,
        },
      ],
    };
  },
  computed: {},
};
</script>

<style></style>
