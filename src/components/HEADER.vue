<template>
<section>
  <topHeader />
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

          <li 
          v-for="(item, index) in menu"
          :key="index"
          @click="isActive(item)"
          >
            <a :href="item.link">
              <span 
              :class="{'active' : item.active === true, 'disactive' : item.active === false}"
              >
              {{item.page}}
              </span>
            </a>
          </li>

        </ul>
        <div class="search">
          <a href="#">
            <i class="fas fa-search"></i>
          </a>
        </div>
      </nav>
    </div>
    <!-- /nav-menu -->

  </header>
</section>
</template>

<script>
import topHeader from './topHeader.vue'
export default {
  name: 'HEADER',
  components: {
   topHeader,
  },
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

      activeItem: ' ',
    }
  },
  methods: {
      isActive(item){
        this.activeItem = item;
        for(let i = 0; i < this.menu.length; i++){
          this.menu[i].active = false;
        }
        this.activeItem.active = true;
      }
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
        width: 100px;
        padding: 25px 0;
      }
    }

    nav{
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 15px 0;
      font-size: 14px;
      ul{
        list-style: none;
        padding: 0;
        display: flex;
        justify-content: start;
        align-items: center;
        margin-bottom: 0;
        li{
          padding-right: 20px;
          height: 100%;
          &:last-of-type{
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
      .search{
        border-left: 2px solid #888888;
        padding-left: 25px;
        a{
          i{
            color: #404040;
          }
        }
      }
    }
  }
}
</style>