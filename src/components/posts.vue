<template>
<section>
  <div class="container posts">
    <div class="row">

      <div class="col-8">

        <!-- post -->
        <div class="post">
          <img src="../assets/img/blog-54.jpg" alt="">
          <div class="post-body">
            <div class="row">
              <div class="col-1">
                <div class="date">
                  <div class="day">
                    12
                  </div>
                  <div class="mounth">
                    Jan
                  </div>
                </div>
              </div>
              <div class="col-11">
                <span class="post-title">How to Make Friends as a Grown-Up</span>
                <p class="post-desc">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem quidem obcaecati molestiae alias quo quos temporibus atque facere accusantium! Iusto facilis nesciunt unde id illo sit laborum, impedit ab optio reprehenderit molestiae maxime ipsam deleniti, quae consequatur dignissimos nobis, voluptate earum asperiores tempore obcaecati ex architecto enim. Quae, voluptatibus dolore?
                </p>
                <div class="info-box">

                  <div class="left-side">
                    <div class="author">
                      <i class="far fa-user"></i>
                      <span>
                        By <a href="#">Jhon Doe</a>
                      </span>
                    </div>
                    <div class="category">
                      <i class="far fa-folder"></i>
                      <span>
                        <a href="#">Lifestyle, Travel</a>
                      </span>
                    </div>
                    <div class="comments">
                      <i class="far fa-comments"></i>
                      <span>
                        <a href="#">12 Comments</a>
                      </span>
                    </div>
                  </div>  

                  <div class="right-side">
                    <button type="button" class="btn btn-light">Read More</button>
                  </div>
                  
                </div>
                <div class="line"></div>
              </div>
            </div>
          </div>
        </div>
        <!-- /post -->
        <!-- post -->
        <div class="post">
          <img src="../assets/img/blog-54.jpg" alt="">
          <div class="post-body">
            <div class="row">
              <div class="col-1">
                <div class="date">
                  <div class="day">
                    12
                  </div>
                  <div class="mounth">
                    Jan
                  </div>
                </div>
              </div>
              <div class="col-11">
                <span class="post-title">How to Make Friends as a Grown-Up</span>
                <p class="post-desc">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem quidem obcaecati molestiae alias quo quos temporibus atque facere accusantium! Iusto facilis nesciunt unde id illo sit laborum, impedit ab optio reprehenderit molestiae maxime ipsam deleniti, quae consequatur dignissimos nobis, voluptate earum asperiores tempore obcaecati ex architecto enim. Quae, voluptatibus dolore?
                </p>
                <div class="info-box">

                  <div class="left-side">
                    <div class="author">
                      <i class="far fa-user"></i>
                      <span>
                        By <a href="#">Jhon Doe</a>
                      </span>
                    </div>
                    <div class="category">
                      <i class="far fa-folder"></i>
                      <span>
                        <a href="#">Lifestyle, Travel</a>
                      </span>
                    </div>
                    <div class="comments">
                      <i class="far fa-comments"></i>
                      <span>
                        <a href="#">12 Comments</a>
                      </span>
                    </div>
                  </div>  

                  <div class="right-side">
                    <button type="button" class="btn btn-light">Read More</button>
                  </div>
                  
                </div>
                <div class="line"></div>
              </div>
            </div>
          </div>
        </div>
        <!-- /post -->

      </div>
        
      <div class="col-4">
      <sidebar />
      </div>
    </div>
  </div>
</section>
</template>

<script>
import sidebar from './sidebar.vue';
export default {
  name: 'postGallery',
  components: {
   sidebar,
  }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
  .posts{
    margin-top: 50px;
    .post{
      margin-bottom: 50px;
      img{
        width: 100%;
      }
      .post-body{
        margin-top: 20px;
        .date{
          text-align: center;
          font-weight: bolder;
          width: 100%;
          .day{
            background-color: #F7F7F7;
            color: $title-color;
            line-height: 50px;
          }
          .mounth{
            text-transform: uppercase;
            color: white;
            background-color: #212529;
            padding: 5px;
            font-size: 12px;
          }
        }
        .post-title{
          color: $title-color;
          font-weight: bolder;
          line-height: 50px;
          font-size: 20px;
        }
        .post-desc{
          font-size: 14px;
          color: #888888;
          line-height: 20px;
          font-weight: 300;
        }
        .info-box{
            color: #888888;
            font-size: 13px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            font-weight: 500;
          .left-side{
            display: flex;
            span{
              margin-right: 10px;
              a{
                color: $main-color;
                text-decoration: none;
              }
            }
            i{
              margin-right: 5px;
            }
          }
          .right-side{
            button{
              color: #888888;
              padding: 2px;
              text-transform: uppercase;
              font-size: 12px;
            }
          }
        }
      }

    }
  }
</style>