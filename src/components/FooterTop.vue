<script>

     export default{
          name: "FooterTop",
          data(){
               return{
                    menuCard: [
                         {
                              img: "/img/buy-comics-digital-comics.png",
                              nome: 'DIGITAL COMICS'
                         },
                         {
                              img: "/img/buy-comics-merchandise.png",
                              nome: 'DC MERCHANDISE'
                         },
                         {
                              img: "/img/buy-comics-subscriptions.png",
                              nome: 'SUBSCRIPTION'
                         },
                         {
                              img: "/img/buy-comics-shop-locator.png",
                              nome: 'COMIC SHOP LOCATOR'
                         },
                         {
                              img: "/img/buy-dc-power-visa.svg",
                              nome: 'DC POWER VISA'
                         },
                    ]
               }
          }
     }

</script>

<template>
     <footer>
          <div class="container">
               <ul>
                    <li v-for="(element, index) in menuCard" :key="index">
                         <img :src="element.img" alt="logo dc footer top">
                         <span>{{ element.nome }}</span>
                    </li>
               </ul>
          </div>
     </footer>
</template>

<style scoped lang="scss">
     footer{
          background-color: #0282f9;
          .container{
               width: 80%;
               padding: 40px 0;
               margin: 0 auto;
          }
          ul{
               display: flex;
               align-items: center;
          }
          li{
               list-style: none;
               margin: 0 20px;
               display: flex;
               align-items: center;
               img{
                    width: 50px;
               }
               span{
                    color: white;
                    margin-left: 5px;
               }
          }
          
     }
</style>