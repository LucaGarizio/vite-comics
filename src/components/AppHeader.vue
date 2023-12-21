<script>
export default{
  name: "AppHeader",
  data() {
    return {
    menuNav: [
        { 
          text: 'CHARACTERS',
          href: '#',
          active: true 
        },
        { 
          text: 'COMICS',
          href: '#', 
          active: false 
        },
        { 
          text: 'MOVIES', 
          href: '#', 
          active: false 
        },
        {
          text: 'TV', 
          href: '#', 
          active: false 
        },
        { 
          text: 'GAMES', 
          href: '#', 
          active: false 
        },
        { 
          text: 'COLLECTIBLES',
          href: '#', 
          active: false 
        },
        { 
          text: 'VIDEOS', 
          href: '#', 
          active: false 
        },
        { 
          text: 'FANS', 
          href: '#', 
          active: false 
        },
        { 
          text: 'NEWS', 
          href: '#', 
          active: false 
        },
        { 
          text: 'SHOP', 
          href: '#', 
          active: false 
        }
      ],
      active: 0
    };
  },
  methods: {
    activeVoice(index){
      this.active = index;
    }
  }
}

</script>

<template>
  <nav>
    <div class="row">
      <div class="logo-col">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="nav-col">
        <ul>
          <li v-for="(voices, index) in menuNav" :key="index" @click="activeVoice(index)">
            <a :class="index === active ? 'active' : ''" :href="voices.href">{{voices.text}}</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>




<style lang="scss" scoped>
// @use'.styles/partials/variables' as *;
// @use '.styles/general/scss' as *; 


  nav{
    background-color: #fff;
  }
  .row{
    margin: 0 auto;
    margin-top: 20px;
    height: 100px;
    width: 80%;
    display: flex;
    justify-content: space-between;
  }
  .logo-col{
    display: flex;
    align-items: center;

    img{
      width: 70px;
    }
  }
  .nav-col{
    display: flex;
    justify-content: flex-end;
    align-items: center;
    
    ul{
      list-style-type: none;
      display: flex;
    }
    
    li{
      margin: 0 20px;
      
      a{
        text-decoration: none;
        color: #436787;
        font-size: 13px;
        
        &:hover {
          color: #2a7ff8;
        }
      }
    }
  }    
    
    .active{
      color: #2a7ff8 !important;
    }
</style>
