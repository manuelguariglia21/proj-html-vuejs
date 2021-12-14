<template>
<section>
  <div class="categorySection">
    <div class="container">

      <i class="fas fa-chevron-left"></i>

      <button type="button" class="btn btn-dark">Dark</button>
      
      
      <button type="button" class="btn btn-dark">Dark</button>
      
      <button type="button" class="btn btn-dark">Dark</button>
      
      <button type="button" class="btn btn-dark">Dark</button>
      
      <button type="button" class="btn btn-dark">Dark</button>

      <i class="fas fa-chevron-right"></i>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'widgetSection',
}
</script>

<style lang="scss" scoped>
  .categorySection{
    height: 90px;
    background-color: #0088CC;
    .container{
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 90px;
      i{
        color: black;
      }
      button{
        width: 16%;
        margin: 0 2%;
      }
    }
  }
</style>