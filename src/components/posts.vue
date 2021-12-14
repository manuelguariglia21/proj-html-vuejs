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
              <div class="col-2">
                <div class="date">
                  <div class="day">
                    12
                  </div>
                  <div class="mounth">
                    Jan
                  </div>
                </div>
              </div>
              <div class="col-10">
                <span class="post-title">How to Make Friends as a Grown-Up</span>
                <p class="post-desc">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem quidem obcaecati molestiae alias quo quos temporibus atque facere accusantium! Iusto facilis nesciunt unde id illo sit laborum, impedit ab optio reprehenderit molestiae maxime ipsam deleniti, quae consequatur dignissimos nobis, voluptate earum asperiores tempore obcaecati ex architecto enim. Quae, voluptatibus dolore?
                </p>
                <div class="info-box">
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
                <div class="line"></div>
              </div>
            </div>
          </div>
        </div>
        <!-- /post -->
      </div>
        
      <div class="col-4">
      
    </div>
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
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
  .posts{
    margin-top: 50px;
    .post{
      img{
        width: 100%;
      }
      .post-body{
        margin-top: 20px;
        .date{
          width: 50%;
          text-align: center;
          font-size: 12px;
          font-weight: bolder;
          .day{
            background-color: #F7F7F7;
            color: black;
            line-height: 50px;
          }
          .mounth{
            text-transform: uppercase;
            color: white;
            background-color: #212529;
          }
        }
        .post-title{
          color: black;
          font-weight: bolder;
          line-height: 50px;
        }
        .post-desc{
          color: black;
          font-size: 14px;
          line-height: 20px;
        }
        .info-box{
          display: flex;
          color: #888888;
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
      }

    }
  }
</style>