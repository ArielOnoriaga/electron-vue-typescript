<template>
  <div class="bg-white">
    <h1 class="text-xl text-red-400">
      {{ message }}
    </h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',

  props: {
    msg:String,
  },

  setup(props) {
    const test:string = "hola";

    return {
      message: `el mensaje es ${props.msg} ${test}`
    }
  }
});
</script>

