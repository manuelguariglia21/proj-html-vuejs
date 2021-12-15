<template>
  <footer>
    <section class="top-footer">
      <div class="container">
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
    </section>
    

    <div class="bottom-footer">
      <div class="container">

        <div class="foot-logo">
          <img src="../assets/img/logo-footer.png" alt="">
          <span>&copy;Copiright 2020. All Rights Reserved.</span>
        </div>

        <div class="foot-menu">
          <ul>
            <li>
              <a href="#">
                <span>
                  <i class="fas fa-chevron-right"></i>
                  FAQ's
                </span>
              </a>
            </li>
            
            <li>
              <a href="#">
                <span>
                  <i class="fas fa-chevron-right"></i>
                  Sitemap
                </span>
              </a>
            </li>
            
            <li>
              <a href="#">
                <span>
                  <i class="fas fa-chevron-right"></i>
                  Contact Us
                </span>
              </a>
            </li>

          </ul>
        </div>

      </div>
      <div class="foot-up">
        <a href="#">
          <i class="fas fa-chevron-up"></i>
        </a>
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
.top-footer{
  width: 100%;
  background-color: #404040;
  .container{
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

.bottom-footer{
  width: 100%;
  background-color: #1C2023;
  min-height: 90px;
  position: relative;
  .container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    line-height: 90px;
    .foot-logo{
      img{
        width: 80px;
        margin-right: 15px;
      }
      span{
        font-size: 12px;
        color: #888888;
      }
    }

    .foot-menu{
      ul{
        list-style: none;
        li{
          display: inline;
          margin-right: 5px;
          a{
            text-decoration: none;
            span{
              color: #888888;
              font-size: 12px;
            }
          }
        }
      }
    }
  }
  .foot-up{
      position: absolute;
      bottom: 0;
      right: 5px;
      height: 50px;
      width: 50px;
      border-top-right-radius: 5px;
      border-top-left-radius: 5px;
      background-color: #888888;

      a{
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        text-decoration: none;
        i{
          color: white;
        }
      }

    }
}
</style>