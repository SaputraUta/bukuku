<template>
  <h2 class="text-3xl font-bold text-slate-800">List of books</h2>
  <Greet class="mt-5" />
</template>

<script lang="ts">
import Greet from "../components/Books.vue";
export default {
  name: "Home",
  components: {
    Greet,
  },
};
</script>
