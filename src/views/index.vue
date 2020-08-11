<template>
  <p>Route: {{ theRoutePath }}</p>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  computed: {
    theRoutePath(): any {
      return this.$route.path;
    },
  },
});
</script>
