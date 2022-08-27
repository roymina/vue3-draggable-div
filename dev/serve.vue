<script>
import { defineComponent } from 'vue';
import Vue3DraggableDiv from '@/vue3-draggable-div.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    Vue3DraggableDiv
  }
});
</script>

<template>
  <div id="app">
    <vue3-draggable-div />
  </div>
</template>
