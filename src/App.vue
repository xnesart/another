<template>
  <!-- <img :src='image'/> -->
  <v-main-wrapper>
    <v-catalog>
      <v-item></v-item>
    </v-catalog>
  </v-main-wrapper>
</template>

<script>
import vMainWrapper from "./components/v-main-wrapper";
import vCatalog from "./components/v-catalog";
import vItem from "./components/v-item";

export default {
  name: "App",
  methods: {},
  components: {
    vMainWrapper,
    vCatalog,
    vItem,
  },
};
</script>

<style>
#app {
  font-family: "Roboto Condensed", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #333333;
  margin-top: 60px;
  font-size: 12px;
}
</style>
