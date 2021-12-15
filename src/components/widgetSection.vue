<template>
<section>
   <div class="container widgetSection">
    <div class="row">
      <!-- popular post -->
      <div class="popular-recent-post col-4">
            <h6>popular post</h6>
            <ul>

              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
            </ul>
      </div>
      <!-- /popular post -->

      <!-- recent post -->
      <div class="popular-recent-post col-4">
            <h6>recent post</h6>
            <ul>

              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              <!-- post -->
              <li>
                <a href="#">
                  <img src="../assets/img/blog-55.jpg" alt="">
                  <div class="post-description">
                    <span class="post-title">Simple Ways to Have a Pretty Face</span>
                    <p class="post-date">January 12, 2019</p>
                  </div>
                </a>
                <div class="line"></div>
              </li>
              <!-- /post -->
              
            </ul>
      </div>
      <!-- /recent post -->

      <!-- featured post -->
      <div class="featured col-4">
        <div class="featured-posts">
          <h6>featured post</h6>
          <div class="image-post">
            <div class="overlay">
              <div class="text-area">
                <div class="btn category-tag">
                  <span>recipes</span>
                </div>
                <div class="title">
                  <p>
                    Tips to help You Quickly Prepare your Lunch
                  </p>
                </div>
                <div class="subtitle">
                  <p>
                    Lorem ipsum dolor sit amet consectetur.
                  </p>
                </div>
              </div>
            </div>
            <img src="../assets/img/blog-66.jpg" alt="featured">
          </div>
        </div>
        <div class="featured-author">
          <h6>featured author</h6>
          <a href="#">
                  <img src="../assets/img/avatar.jpg" alt="">
                  <div class="author-description">
                    <span class="author-title">Jhon Doe</span>
                    <p class="author-desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate, repellat.</p>
                  </div>
                </a>
        </div>
      </div>
      <!-- /featured post -->
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
  .widgetSection{
    margin-top: 50px;
    .popular-recent-post{
      ul{
        list-style: none;
        padding: 0;
        li{
          padding-top: 10px;
          a{
            display: flex;
            justify-content: start;
            align-content: center;
            position: relative;
            text-decoration: none;
            img{
              width: 50px;
              height: 50px;
              margin-right: 5px;
            }

            .post-description{
              .post-title{
              color: black;
              font-size: 15px;

              }
              .post-date{
              color: #978F9B;
              font-size: 14px;
              }
            }
          }
        }
      }
      
    }
  }

  .featured{
    .featured-posts{
      .image-post{
        position: relative;
        img{
          width: 100%;
        }
      }
    }
    .featured-author{
      a{
            display: flex;
            justify-content: start;
            align-content: center;
            position: relative;
            text-decoration: none;
            flex-wrap: wrap;
        img{
          width: 38%;
          margin-right: 4%;
        }
        .author-description{
          width: 58%;
          .author-title{
            font-size: 15px;
            font-weight: bolder;
            color: black;
          }
          .author-desc{
            color: #978F9B;
          }
        }
      }
    }
  }
  h6{
        color: black;
        text-transform: uppercase;
        font-weight: bolder;
      }
</style>