<template>
  <div>
    <HeaderComponent />
    <MainComponent />
    <ShopComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MainComponent from "./components/MainComponent.vue";
import ShopComponent from "./components/SectionComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";




export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    ShopComponent,
    FooterComponent,
    
}
}
</script>

<style lang="scss">

@import './assets/style/global';
@import './assets/style/utilities';
@import './assets/style/vars';


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
