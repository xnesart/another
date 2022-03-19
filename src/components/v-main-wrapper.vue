<template>
  <div class="v-main-wrapper">
    <v-catalog>
      <v-item></v-item>
    </v-catalog>
  </div>
  <div class="pagination">
    <ul class="pagination__list">
      <li class="pagination__item"><a href="#" class="pagination__value">1</a></li>
      <span>...</span>
      <li class="pagination__item"><a href="#" class="pagination__value">4</a></li>
      <li class="pagination__item pagination__item_current"><a href="#" class="pagination__value">5</a></li>
      <li class="pagination__item"><a href="#" class="pagination__value">6</a></li>
      <span>...</span>
      <li class="pagination__item"><a href="#" class="pagination__value">59</a></li>
    </ul>
  </div>
</template>

<script>
import vCatalog from "./v-catalog";
import vItem from "./v-item";
export default {
  name: "v-main-wrapper",
  components: {
    vCatalog,
    vItem,
  },
};
</script>

<style>

</style>
