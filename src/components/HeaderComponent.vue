<template>
  <header class="container d-flex">

    <div class="row">
      <div class="col-2 offset-2">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="col-2 offset-2 d-flex justify-content-cente align-items-center">
        <ul class="d-flex">
          <li :class="{'active' : menu.isActive}" v-for="(menu, index) in HeaderMenu" :key="`menu-${index}`">
            <a :href="menu.href">{{menu.name}}</a>
          </li>
        </ul>
      </div>
    </div>
    
  </header>
</template>

<script>
export default {
  name:'HeaderComponent',
  data() {
    return {
      HeaderMenu: [
        {
          name: 'characters',
          href: '#',
          isActive: false
        },
        
        {
          name: 'comics',
          href: '#',
          isActive: true
        },
        {
          name: 'movies',
          href: '#',
          isActive: false
        },
        {
          name: 'tv',
          href: '#',
          isActive: false
        },
        {
          name: 'games',
          href: '#',
          isActive: false
        },
        {
          name: 'collectibles',
          href: '#',
          isActive: false
        },
        {
          name: 'videos',
          href: '#',
          isActive: false
        },
        {
          name: 'fans',
          href: '#',
          isActive: false
        },
        {
          name: 'news',
          href: '#',
          isActive: false
        },
        {
          name: 'shop',
          href: '#',
          isActive: false
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

header {
  margin: 15px 0;
}

ul {
  


  li {
    padding: 0px 23px;

    a {
      text-transform: uppercase;
      color: #4e455d;

      &:hover{
        color: #0281fa;
      }
    }

    .active{
      border-bottom: 3px solid #0281fa;;
    }
  }
}

</style>