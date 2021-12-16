<template>
<section>
  <div class="categorySection">
    <div class="container">

      <i class="fas fa-chevron-left"></i>
      
      
      <button type="button" class="btn btn-porto">gadgets</button>
      <button type="button" class="btn btn-porto">photography</button>
      <button type="button" class="btn btn-porto">lifestyle</button>
      <button type="button" class="btn btn-porto">fashion</button>
      <button type="button" class="btn btn-porto">recipes</button>
      <button type="button" class="btn btn-porto">travel</button>
      
      

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
    background-color: #0088CC;
        padding: 50px 0;
    .container{
      display: flex;
      justify-content: space-between;
      align-items: center;
      i{
        color: #404040;
        cursor: pointer;
      }
      button{
        width: 16%;
        margin: 0 2%;
        padding: 10px 15px;
        font-size: 14px;
      }
    }
  }
</style>