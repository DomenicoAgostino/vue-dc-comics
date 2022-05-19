<template>
  <div>
    <HeaderComponent />
    <JumbotronComponent />
    <MainComponent />
    <ShopComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import JumbotronComponent from "./components/JumbotronComponent.vue";
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
    JumbotronComponent
}
}
</script>

<style lang="scss">

@import './assets/style/global';
@import './assets/style/utilities';
@import './assets/style/vars';


</style>
