<script>

     export default{
          name: "FooterBottom",
          data(){
               return{

               }
          }
     }

</script>

<template>
     <footer>
          <div class="container">
               
               <a href="">SIGN-UP NOW!</a>

               <div>
                    <span>FOLLOW US</span>
                    <img src="/img/footer-facebook.png" alt="">
                    <img src="/img/footer-twitter.png" alt="">
                    <img src="/img/footer-youtube.png" alt="">
                    <img src="/img/footer-pinterest.png" alt="">
                    <img src="/img/footer-periscope.png" alt="">
               </div>
          </div>
     </footer>
</template>

<style scoped lang="scss">
     footer{
          background-color: #303030;
          .container{
               width: 80%;
               margin: 0 auto;
               padding: 20px 0;
               display: flex;
               justify-content: space-between;
               align-items: center;
               a{
                    color: white;
                    border: 2px solid #0282f9;
                    padding: 10px;
                    text-decoration: none;
               }
               div{
                    display: flex;
                    align-items: center;
                    span{
                         color: #0282f9;
                    }
                    img{
                         margin: 0 10px;
                    }
               }
               
          }
     }
</style>