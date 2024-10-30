<template>
  <header>
    <nav class="flex items-center justify-between p-4 bg-slate-500">
      <div class="bg-slate-400 hover:bg-slate-600 cursor-pointer text-white rounded-full p-3">
        Logo
      </div>
      <HeaderLinks />
    </nav>
  </header>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import HeaderLinks from './HeaderLinks.vue';
  export default defineComponent({
    name : 'HeaderComponent',
    components : {
      HeaderLinks
    }
  })
</script>

<style scoped>
  
</style>