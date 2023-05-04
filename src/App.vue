<script>

  import HeaderComp from './components/HeaderComp.vue';
  import MainComp from './components/MainComp.vue';
  import FooterTop from './components/FooterTop.vue';
  import FooterMid from './components/FooterMid.vue';
  import FooterBottom from './components/FooterBottom.vue';

  export default{
    name: "App",
    components: {
      HeaderComp,
      MainComp,
      FooterTop,
      FooterMid,
      FooterBottom,
    }
  }

</script>

<template>
  <HeaderComp/>
  <MainComp/>
  <FooterTop/>
  <FooterMid/>
  <FooterBottom/>
</template>

<style lang="scss">
  @use './style/main.scss'
</style>
