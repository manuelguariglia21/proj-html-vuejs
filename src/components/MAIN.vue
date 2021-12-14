<template>
  <main>
    <postGallery />
    <widgetSection />
    <categorySection />
  </main>
</template>

<script>
import postGallery from './postGallery.vue';
import widgetSection from './widgetSection.vue';
import categorySection from './categorySection.vue';
export default {
  name: 'MAIN',
  components: {
   postGallery,
   widgetSection,
   categorySection
  }
}
</script>

<style>
main{
  width: 100%;
}
</style>