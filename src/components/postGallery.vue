<template>
<section>
   <div class="container postGallery">
    <div class="row">

      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      
      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      
      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      
      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      
      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="how">
      </div>
      <!-- /postCard -->
      
      
      <!-- postCard -->
      <div class="postCard col-4">
        <div class="overlay">
          <div class="text-area">
            <div class="btn category-tag">
              <span>photography</span>
            </div>
            <div class="title">
              <p>
                How To Take Better Concert Pictures in 30 Seconds
              </p>
            </div>
            <div class="subtitle">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
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
        position: relative;
        background-color: salmon;
        border: 5px solid #F7F7F7;
        padding: 0;
        cursor: pointer;
        
        img{
          width: 100%;
        }
        .overlay{
          &:hover{
            .text-area{
              .subtitle{
                visibility: visible;
              }
            }
          }
          .text-area{
            display: flex;
            flex-direction: column;
            justify-content: end;
            .subtitle{
              visibility: collapse;
            }
          }
        }
      }
  }
}
</style>