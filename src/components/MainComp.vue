<script>

     export default{
          name: "MainComp",
          data(){
               return{

               }
          }
     }

</script>

<template>
     <main>
          <div class="container">
               <h2> --content goes here--</h2>
          </div>
     </main>
</template>

<style scoped lang="scss">
     main{
          background-color: #1c1c1c;
          margin-top: 5px;
          .container{
               width: 80%;
               margin: 0 auto;
               padding: 20px 0;
               h2{
                    color: white;
               }

          }
     }
</style>