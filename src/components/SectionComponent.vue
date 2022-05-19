<template>
<section>
<div class="shop d-flex align-items-center">
  <div class="container">
    <nav>
      <ul class="d-flex">
        
        <li>
          <a href="">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
            digital comics
          </a>
        </li>

        <li>
          <a href="">
            <img src="../assets/img/buy-comics-merchandise.png" alt="Digital Comics">
            dc merchandise
          </a>
        </li>

        <li>
          <a href="">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="Digital Comics">
            subscription
          </a>
        </li>

        <li>
          <a href="">
            <img class="locator" src="../assets/img/buy-comics-shop-locator.png" alt="Digital Comics">
            comic shop locator
          </a>
        </li>

        <li>
          <a href="">
            <img class="visa" src="../assets/img/buy-dc-power-visa.svg" alt="Digital Comics">
            dc power visa
          </a>
        </li>

      </ul>
    </nav>
  </div>
</div>

</section>


</template>

<script>
export default {
  name: 'SectionComponent'
}
</script>

<style lang="scss" scoped>

 .shop {
    background-color: #0282F9;
    height: 200px;
  }
  img {
    width: 25%;
  }
  li {
    padding: 0px 10px ;
    a {
      color: #FFFFFF;
      img {
        margin-right: 10px;
      }
    }
  } 
  
  .power-visa {
    width: 19%;
  }
  .locator {
    width: 17%;
  }

</style>