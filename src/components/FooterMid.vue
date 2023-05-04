<script>

     export default{
          name: "FooterMid",
          data(){
               return{

               }
          }
     }

</script>

<template>
     <footer>
          <div class="container">
               <div >
                    <h3>DC COMICS</h3>
                    <ul>
                         <li><a>Characters</a></li>
                         <li><a>Comics</a></li>
                         <li><a>Movies</a></li>
                         <li><a>TV</a></li>
                         <li><a>Games</a></li>
                         <li><a>Videos</a></li>
                         <li><a>News</a></li>
                    </ul>
                    <br>
                    <h3>SHOP DC</h3>
                    <ul>
                         <li><a>Shop DC</a></li>
                         <li><a>Shop DC Collectibles</a></li>
                    </ul>
               </div>
               <div>
                    <h3>DC</h3>
                    <ul>
                         <li><a>Terms Of Use</a></li>
                         <li><a>Privacy Policy</a></li>
                         <li><a>Ad Choices</a></li>
                         <li><a>Advertising</a></li>
                         <li><a>Jobs</a></li>
                         <li><a>Subscriptions</a></li>
                         <li><a>Talent Workshops</a></li>
                         <li><a>TCPSC Certificates</a></li>
                         <li><a>Ratings</a></li>
                         <li><a>Shop Helps</a></li>
                         <li><a>Contacts Us</a></li>
                    </ul>
               </div>
               <div>
                    <h3>SITES</h3>
                    <ul>
                         <li><a>DC</a></li>
                         <li><a>MAD Magazine</a></li>
                         <li><a>DC Kids</a></li>
                         <li><a>DC Universe</a></li>
                         <li><a>DC Power Visa</a></li>
                    </ul>
               </div>
          </div>
     </footer>
</template>

<style scoped lang="scss">
     footer{
          background-image: url('/img/footer-bg.jpg');
          background-repeat: no-repeat;
          background-size: cover;
          .container{
               width: 80%;
               margin: 0 auto;
               padding: 30px 0;
               display: flex;
               background-image: url('/img/dc-logo-bg.png');
               background-repeat: no-repeat;
               background-position: center right;
               background-size: 35%;
               div{
                    margin-right: 30px;
                    h3{
                         color: white;
                         margin-bottom: 10px;
                    }
                    ul{ 
                         li{
                              list-style: none;
                              color: grey;
                              font-size: smaller;
                              margin-bottom: 2px;
                         }
                    }
               }
          }
     }
</style>