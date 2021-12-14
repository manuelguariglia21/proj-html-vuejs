<template>
  <main>
    <postGallery />
    <widgetSection />
    <categorySection />
    <posts />
  </main>
</template>

<script>
import postGallery from './postGallery.vue';
import widgetSection from './widgetSection.vue';
import categorySection from './categorySection.vue';
import posts from './posts.vue';
export default {
  name: 'MAIN',
  components: {
   postGallery,
   widgetSection,
   categorySection,
   posts
  }
}
</script>

<style>
main{
  width: 100%;
}
</style>