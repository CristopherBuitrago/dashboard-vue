<template>
  <main class="grid lg:grid-cols-6 sm:grid-cols-3 grid-rows-2 gap-2 m-5 p-5 ">
    <DescriptionMain />
    <FeaturesMain />
    <SocialMedia />
  </main>
</template>

<script lang="ts" setup>
  import DescriptionMain from './DescriptionMain.vue';
  import FeaturesMain from './FeaturesMain.vue';
  import SocialMedia from './SocialMedia.vue';
</script>

<style scoped>

</style>