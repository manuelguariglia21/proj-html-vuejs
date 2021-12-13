<template>
  <main>
    <postGallery />
  </main>
</template>

<script>
import postGallery from './postGallery.vue';
export default {
  name: 'MAIN',
  components: {
   postGallery,
  }
}
</script>

<style>
main{
  width: 100%;
}
</style>