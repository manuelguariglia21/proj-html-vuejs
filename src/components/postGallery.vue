<template>
<section>
   <div class="container postGallery">
    <div class="row">

      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      <!-- postCard -->
      <div class="postCard col-4">
        <img src="../assets/img/blog-46.jpg" alt="how">
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
        background-color: salmon;
        border: 5px solid #F7F7F7;
        padding: 0;
        img{
          width: 100%;
        }
      }
  }
  }
</style>