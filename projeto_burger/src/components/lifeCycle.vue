<template>
  <h1>My name is: {{}}</h1>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "lifeCycle",
  data() {
    return {
      nome: "slim shady",
    };
  },
});
</script>
