<template>
<section>
   <div class="container postGallery">
    <div class="row">
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="" alt="">
      </div>
      <!-- /postCard -->

      <!-- postCard -->
      <div class="postCard col-4">
        <img src="" alt="">
      </div>
      <!-- /postCard -->
      
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="" alt="">
      </div>
      <!-- /postCard -->
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'postGallery',
}
</script>

<style lang="scss" scoped>
  section{
    width: 100%;
    background-color: #F7F7F7;
    .postGallery{
    background-color: red;
    min-height: 200px;
    .postCard{
      min-height: 250px;
      background-color: salmon;
      border: 5px solid #F7F7F7;
    }
  }
  }
</style>