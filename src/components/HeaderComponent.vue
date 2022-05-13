<template>
  <header class="container d-flex">

    <div class="row">
      <div class="col-2 offset-2">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="col-2 offset-2 d-flex justify-content-cente align-items-center">
        <nav>
      <ul class="d-flex">

        <li>
          <a href="">characters</a>
        </li>

        <li>
          <a href="">comics</a>
        </li>

        <li>
          <a href="">movies</a>
        </li>


        <li>
          <a href="">tv</a>
        </li>


        <li>
          <a href="">games</a>
        </li>


        <li>
          <a href="">collectibles</a>
        </li>


        <li>
          <a href="">videos</a>
        </li>


        <li>
          <a href="">fans</a>
        </li>

    
        <li>
          <a href="">news</a>
        </li>


        <li>
          <a href="">shop</a>
        </li>

      </ul>

    </nav>
      </div>
    </div>
    
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent'
}
</script>

<style lang="scss" scoped>

header {
  margin: 15px 0;
}

ul {
  list-style: none;


  li {
    padding: 0px 23px;

    a {
      text-transform: uppercase;
      text-decoration: none;
      color: #4e455d;

      &:hover{
        color: #0281fa;
      }
    }
  }
}

</style>