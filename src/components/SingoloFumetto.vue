<script>

export default{
     name: "SingoloFumetto",
     props: ['infoFumetto']
    
}

</script>

<template>
     <div>
          <img :src="infoFumetto.thumb" alt="fumetto">
          <h4>{{ infoFumetto.series }}</h4>
     </div>
</template>

<style scoped lang="scss">
     div{
          width: calc(100% / 6 - 10px);
          img{
               width: 100%;
               height: 80%;
               margin-bottom: 10px;

          }
          h4{
               text-transform: uppercase;
          }
     }
</style>