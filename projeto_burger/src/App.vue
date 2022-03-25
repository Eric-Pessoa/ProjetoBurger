<template>
  <componente1 />
  <lifeCycle />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import componente1 from "./components/componente1.vue";
import lifeCycle from "./components/lifeCycle.vue";
export default defineComponent({
  name: "App",
  components: {
    componente1,
    lifeCycle,
  },
});
</script>
