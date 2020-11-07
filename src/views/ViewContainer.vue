<template>
  <div class="flex flex-row">
    <Dashboard />

    <slot />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Dashboard from "../components/Dashboard.vue";

export default defineComponent({
  name: 'ViewContainer',

  components: {
    Dashboard
  }
})

</script>