<template>
  <section>

    <div class="last-twitter">
      <h6>latest from twitter</h6>

      <div class="tweet">
        <i class="fab fa-twitter"></i>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit.
          <span class="tweet-date">
          01:05 PM Sep 18th
          </span>  
        </p>
      </div>

      <div class="tweet">
        <i class="fab fa-twitter"></i>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit.
          <span class="tweet-date">
          01:05 PM Sep 18th
          </span>  
        </p>
      </div>
      
    </div>

    <div class="instagram-photos">

      <h6>photos from instagram</h6>

      <div class="ig-grid">
        <img src="../assets/img/29739607_2020680068220520_4509928046932787200_n.jpg" alt="">
        <img src="../assets/img/30087804_253872848488989_8792603541668626432_n.jpg" alt="">
        <img src="../assets/img/29415620_196477127626244_3250318472361541632_n.jpg" alt="">
        <img src="../assets/img/30078414_1274410412703843_8290935809419247616_n.jpg" alt="">
        <img src="../assets/img/30077195_2066750973610181_3733150062893596672_n.jpg" alt="">
        <img src="../assets/img/29415304_166583630713703_1032667922171953152_n.jpg" alt="">
      </div>

    </div>

    <div class="tags">
      <h6>tags</h6>
      <div class="tags-box">
        <button type="button" class="btn btn-porto radius">design</button>
        <button type="button" class="btn btn-porto radius">brands</button>
        <button type="button" class="btn btn-porto radius">video</button>
        <button type="button" class="btn btn-porto radius">business</button>
        <button type="button" class="btn btn-porto radius">travel</button>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  name: 'sidebar',
}
</script>

<style lang="scss">
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
section{
  .last-twitter{
    .tweet{
      display: flex;
      i{
        font-size: 25px;
        color: black;
        margin-right: 15px;
      }
      p{
        color: #888888;
        .tweet-date{
          color: $main-color;
          display: block;
        }
      }
    }
  }

  .ig-grid{
    display: flex;
    flex-wrap: wrap;
    margin-bottom: 20px;
    img{
      width: calc(100% / 3);
    }
  }
  h6{
    font-weight: bolder;
    color: black;
    text-transform: uppercase;
  }
}
</style>