<template>
  <div class="container">
    <ListMemes />
  </div>
</template>

<script>
import ListMemes from "./components/ListMemes";
import { useStore } from "vuex";

export default {
  name: "App",
  components: {
    ListMemes,
  },
};
</script>

<style></style>
