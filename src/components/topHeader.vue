<template>
  <section>
    <div class="container">
      <p>Everything about Lifestyle, Travel and Gadgets!</p>

    <div class="header-top-menu">
          <ul>
            <li>
              <a href="#">
                <span>
                  SIGN IN
                </span>
              </a>
            </li>
            
            <li>
              <a href="#">
                <span>
                  ABOUT US
                </span>
              </a>
            </li>
            
            <li>
              <a href="#">
                <span>
                  CONTACT US
                </span>
              </a>
            </li>

            <li>
              <a href="#">
                <span>
                  BUY NOW
                </span>
              </a>
            </li>

          </ul>
        </div>
    </div>

  </section>
</template>

<script>
export default {
  name: 'topHeader',
}
</script>

<style lang="scss" scoped>
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
section{
  width: 100%;
  background-color: $main-color;
  color: white;
  font-weight: 300;
  .container{
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding: 15px 0;
    p{
      margin-bottom: 0;
    }
  }
  .header-top-menu{
    ul{
      display: flex;
      margin-bottom: 0;
      li{
        font-size: 14px;
        list-style: none;
        margin-right: 20px;
        a{
          text-decoration: none;
          span{
            color: white;
            text-transform: uppercase;
            font-weight: 500;
          }
        }
      }
    }
  }
}
</style>