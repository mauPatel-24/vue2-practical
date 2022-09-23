<template>
  <Header></Header>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "../components/Header-new.vue";

export default Vue.extend({
  name: "Home",

  components: {
    Header,
  },
});
</script>
