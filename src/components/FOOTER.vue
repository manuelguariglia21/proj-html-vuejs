<template>
  <footer>
    <div class="top-footer container">
      <div class="row">

        <div class="about col-3">
          <h6 class="foot-title">ABOUT THE BLOG</h6>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae, nobis?</p>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi, non!</p>
          <p>
            <a href="#">
              <span class="more">
                VIEW MORE
              </span>
              <i class="fas fa-chevron-right"></i>
            </a>
          </p>
        </div>

        <div class="recent col-3">
          <h6 class="foot-title">RECENT POST</h6>

          <div class="post">
            <img src="../assets/img/our-office-4-square.jpg" alt="">
            <div class="post-desc-foot">
              <p class="post-desc">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vitae, necessitatibus.
              </p>
              <p class="foot-date">
                12:53 AM Dec 19th
              </p>
            </div>
          </div>

          <div class="post">
            <img src="../assets/img/our-office-5-square.jpg" alt="">
            <div class="post-desc-foot">
              <p class="post-desc">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vitae, necessitatibus.
              </p>
              <p class="foot-date">
                12:53 AM Dec 19th
              </p>
            </div>
          </div>
          
        </div>

        <div class="recent-comments col-3">
          <h6 class="foot-title">Recent comments</h6>

          <!-- comment -->
          <div class="comment">
            <p>
              <i class="fas fa-chevron-right"></i>
              <span class="author-name">
                John Doe
              </span>
              comment on
              <span class="author-comment">
                lorem ipsum dolor sit amet.
              </span>
            </p>
            <p class="foot-date">
                12:53 AM Dec 19th
            </p>
          </div>
          <!-- /comment -->
          
          <!-- comment -->
          <div class="comment">
            <p>
              <i class="fas fa-chevron-right"></i>
              <span class="author-name">
                John Doe
              </span>
              comment on
              <span class="author-comment">
                lorem ipsum dolor sit amet.
              </span>
            </p>
            <p class="foot-date">
                12:53 AM Dec 19th
            </p>
          </div>
          <!-- /comment -->

        </div>

        <div class="categories col-3">
          <h6 class="foot-title">
            categories
          </h6>

          <div class="tags-box">
              <button type="button" class="btn btn-dark">design</button>
              <button type="button" class="btn btn-dark">brands</button>
              <button type="button" class="btn btn-dark">video</button>
              <button type="button" class="btn btn-dark">business</button>
              <button type="button" class="btn btn-dark">travel</button>
              <button type="button" class="btn btn-dark">design</button>
              <button type="button" class="btn btn-dark">brands</button>
              <button type="button" class="btn btn-dark">video</button>
              <button type="button" class="btn btn-dark">business</button>
              <button type="button" class="btn btn-dark">travel</button>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'footer',
}
</script>

<style lang="scss">
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
footer{
  width: 100%;
  background-color: #404040;
  .top-footer{
    padding-top: 50px;
    .row{

      //generals
        .foot-title, .more, i{
          color: white
        }
        i, .more, .foot-date{
          font-size: 12px;
        }
        .foot-title{
          font-weight: bolder;
          text-transform: uppercase;
        }
        p{
          color: #888888;
          a{
            text-decoration: none;
          }
        }

        //recent posts
        .recent{
          .post{
            display: flex;
            flex-wrap: wrap;
            .post-desc-foot{
              width: calc(100% - 90px);
              .post-desc{
              color: white;
              font-weight: bolder;

              }
            }
            img{
                width: 70px;
                height: 70px;
                margin-right: 20px;
                border-radius: 50%;
                margin-bottom: 20px;
                display: inline-block;
             }
          }
        }

        //recent comments
        .recent-comments{
          .comment{
            i{
              color: $main-color;
              margin-right: 5px;
            }
            p{
              color: white;
              .author-name, .author-comment{
              font-weight: bolder;
              }
              .author-comment{
                color: $main-color;
              }
            }

            .foot-date{
              color: #888888;
            }
            
            
          }
        }

        //categories

          .categories{
            .tags-box{
              button{
                margin: 2px;
              }
            }
          }
      }
    }
  }
</style>