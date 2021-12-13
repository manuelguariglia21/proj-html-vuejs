<template>
  <header>
    <!-- logo -->
    <div class="container">
      <div class="logo">
        <img src="../assets/img/logo-default-slim.png" alt="">
      </div>
    </div>
    <!-- /logo -->

    <!-- line -->
    <div class="line"></div>
    <!-- /line -->

    <!-- nav-menu -->
    <div class="container">
      <nav>
        <ul>

          <li v-for="(item, index) in menu" :key="index"><a :href="item.link">
            <span :class="{'active' : item.active === true, 'disactive' : item.active === false}">{{item.page}}</span>
            </a></li>

        </ul>
      </nav>
    </div>
    <!-- /nav-menu -->

  </header>
</template>

<script>
export default {
  name: 'HEADER',
  data(){
    return{
      menu: [
        {
          page: 'Home',
          link: '#',
          active: true,
        },
        {
          page: 'Elements',
          link: '#',
          active: false,
        },
        {
          page: 'Features',
          link: '#',
          active: false,
        },
        {
          page: 'Pages',
          link: '#',
          active: false,
        },
        {
          page: 'Portfolio',
          link: '#',
          active: false,
        },
        {
          page: 'Blog',
          link: '#',
          active: false,
        },
        {
          page: 'Shop',
          link: '#',
          active: false,
        },
      ],
    }
  },
  methods: {
      
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";
header{
  width: 100%;
  .container{

    .logo{
      img{
        width: 150px;
        padding: 15px 0;
      }
    }

    nav{
      margin-top: 15px;
      ul{
        list-style: none;
        padding: 0;
        display: flex;
        justify-content: start;
        align-items: flex-start;
        li{
          padding-left: 25px;
          &:first-of-type{
            padding-left: 0;
          }
          a{
            text-decoration: none;
            span{
              text-transform: uppercase;
              font-weight: bolder; 
            }
          }
        }
      }
    }
  }
}
</style>