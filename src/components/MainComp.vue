<script>

     import ContainerFumetti from './ContainerFumetti.vue';

     export default{
          name: "MainComp",
          components: {
               ContainerFumetti
          },
          data(){
               return{

               }
          }
     }

</script>

<template>
     <main>
          <div id="jumbotron">

          </div>
          <div class="container">
               <div id="titolo-serie">
                    <h3>CURRENT SERIES</h3>
               </div>
               
               <ContainerFumetti/>
          </div>
     </main>
</template>

<style scoped lang="scss">
     main{
          background-color: #1c1c1c;
          margin-top: 5px;
          #jumbotron{
               background-image: url('/img/jumbotron.jpg');
               height: 400px;
               background-repeat: no-repeat;
               background-size: cover;
          }
          .container{
               width: 80%;
               margin: 0 auto;
               padding: 20px 0;
               color: white;
               #titolo-serie{
                    background-color: #0282f9;
                    display: inline-block;
                    padding: 10px;
                    position: relative;
                    top: -40px;
               }
          }
     }
</style>