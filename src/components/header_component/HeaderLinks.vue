<template>
  <ul class="flex space-x-4 text-white">
    <li>
      <a href="#" class="hover:text-gray-300 transition-colors">Dashboard</a>
    </li>
    <li>
      <a href="#" class="hover:text-gray-300 transition-colors">Posts</a>
    </li>
    <li>
      <a href="#" class="hover:text-gray-300 transition-colors">Saved</a>
    </li>
  </ul>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  export default defineComponent({
    name : 'HeaderLinks'
  })
</script>

<style scoped>

</style>