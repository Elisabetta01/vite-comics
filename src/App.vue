<script>

  import HeaderComp from './components/HeaderComp.vue';
  import MainComp from './components/MainComp.vue';
  import FooterTop from './components/FooterTop.vue';
  import FooterMid from './components/FooterMid.vue';

  export default{
    name: "App",
    components: {
      HeaderComp,
      MainComp,
      FooterTop,
      FooterMid,
    }
  }

</script>

<template>
  <HeaderComp/>
  <MainComp/>
  <FooterTop/>
  <FooterMid/>
</template>

<style lang="scss">
  @use './style/main.scss'
</style>
