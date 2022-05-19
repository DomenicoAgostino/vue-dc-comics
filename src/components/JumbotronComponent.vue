<template>
  <div class="jumbotron container-fluid">
    <div class="container">
      <span>current series</span>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'JumbotronComponent'
}
</script>

<style lang="scss" scoped>

.jumbotron {
  background-image: url(../assets/img/jumbotron.jpg);
  height: 350px;
}

span {
    text-transform: uppercase;
    background-color: #0282F9;
    color:white;
    font-size: 30px;
    padding: 5px 20px;
    position: absolute;
    bottom: 45%;
    left: 22%;
  }


</style>