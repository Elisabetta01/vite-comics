<script>

  import HeaderComp from './components/HeaderComp.vue';
  import MainComp from './components/MainComp.vue';
  import FooterTop from './components/FooterTop.vue';

  export default{
    name: "App",
    components: {
      HeaderComp,
      MainComp,
      FooterTop,
    }
  }

</script>

<template>
  <HeaderComp/>
  <MainComp/>
  <FooterTop/>
</template>

<style lang="scss">
  @use './style/main.scss'
</style>
