<template>
  <h1>{{ nome }}</h1>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "componente1",
  data() {
    return {
      nome: "Eric",
    };
  },
});
</script>
