<script lang="ts">
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { ToolkitSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  ToolkitSample,
  // }
});
</script>

<template>
  <div id="app">
    <toolkit-sample />
  </div>
</template>
