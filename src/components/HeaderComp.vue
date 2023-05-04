<script>

     export default{
          name: "HeaderComp",
          data(){
               return{
                    menu: [
                         {
                              nome: 'characters',
                              current: false
                         },
                         {
                              nome: 'comics',
                              current: true
                         },
                         {
                              nome: 'movies',
                              current: false
                         },
                         {
                              nome: 'tv',
                              current: false
                         },
                         {
                              nome: 'games',
                              current: false
                         },
                         {
                              nome: 'collectibles',
                              current: false
                         },
                         {
                              nome: 'videos',
                              current: false
                         },
                         {
                              nome: 'fans',
                              current: false
                         },
                         {
                              nome: 'news',
                              current: false
                         },
                         {
                              nome: 'shop',
                              current: false
                         },

                    ]
               }
          }
     }

</script>

<template>
  <header>
     <nav>
          <img src="/img/dc-logo.png" alt="">

          <ul>
               <li v-for="(element, index) in menu" :key="index"
               :class="element.current ? 'active' : '' ">
                    <a href="">{{ element.nome }}</a>
               </li>
          </ul>

     </nav>
  </header>
</template>

<style scoped lang="scss">
     header{
          height: 100px;
          nav{
               display: flex;
               justify-content: space-between;
               align-items: center;
               width: 80%;
               margin: 0 auto;
               img{
                    width: 80px;
               }
               ul{
                    display: flex;
                    li{
                         list-style: none;
                         margin: 0 10px;
                         line-height: 100px;
                         a{
                              text-decoration: none;
                              color: black;
                              text-transform: uppercase; 
                         }
                         &.active {
                              border-bottom: 5px solid blue; 
                         }
                         &.active a {
                              color: blue;
                         }
                         &:hover {
                              border-bottom: 5px solid blue; 
                         }
                         &:hover a{
                              color: blue; 
                         }
                    }
               
               }
          }
     }

</style>