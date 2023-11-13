<script >
</script>

<template>
<div class="bgpag3">
   <div class="pag3">
      <h1>
         THE ANSWER
IS GRACE
      </h1>
      <div class="card1">

         <div class="leftcard1">
            <div class="numbercard">
            <span>1</span>   
            </div>
            <div class="textcard">
               <h2>aminoacidi</h2>
               <span class="higher">100% higher</span>
               <p>On average, GRACE yolks' amino acidslevel is 100% higher than other yolks</p>
               <span class="buy">buy</span>
            </div>

         </div>
         <div class="rightcard1">
            <img src="https://grace.energy/wp-content/uploads/2023/06/grace-box.jpg" alt="">
         </div> 
      </div>
      <div class="card2">

         <div class="leftcard1">
            <div class="numbercard">
            <span>1</span>   
            </div>
            <div class="textcard">
               <h2>aminoacidi</h2>
               <span class="higher">100% higher</span>
               <p>On average, GRACE yolks' amino acidslevel is 100% higher than other yolks</p>
               <span class="buy">buy</span>
            </div>

         </div>
         <div class="rightcard1">
            <img src="https://grace.energy/wp-content/uploads/2023/06/grace-box.jpg" alt="">
         </div> 
      </div>
         
   </div>
</div>
</template>

<style scoped lang="scss">

.bgpag3{
   background-color: black;

   .pag3{
   width:90%;
   margin: auto;
   padding-top:50px ;
   color:white;

   .card1{
      width: 100%;
      display:flex;
      .leftcard1{
         width: 60%;
         display: flex;
         .numbercard{
            width: 10%;
            display: flex;
            justify-content: center;
            padding-top: 200px;
            font-size: 30px;
          span{
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border: 2px solid #fbed3f;
            border-radius:50%;
            color: #fbed3f;
          }
         }
         .textcard{
            width:90%;
            h2{
               padding-top: 200px;
               font-size: 30px;
               padding-bottom: 20px;
            }  
            .higher{
               opacity: .6;
               font-size: 20px;
            }
            p{
               padding-top:20px;
               font-size: 20px;
               padding-bottom: 20px;
            }
            .buy{
               background-color: #fbed3f;
               font-size: 20px;
               color:black;
               padding: 5px 3px 0 3px;
            }
         }   
      }
      .rightcard1{

      }
   }  
   .card2{
      display:flex;
      flex-direction: row-reverse;
      width: 100%;
      display:flex;
      .leftcard1{
         width: 40%;
         display: flex;
         .numbercard{
            width: 10%;
            display: flex;
            justify-content: center;
            padding-top: 200px;
            font-size: 30px;
          span{
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border: 2px solid #fbed3f;
            border-radius:50%;
            color: #fbed3f;
          }
         }
         .textcard{
            width:90%;
            h2{
               padding-top: 200px;
               font-size: 30px;
               padding-bottom: 20px;
            }  
            .higher{
               opacity: .6;
               font-size: 20px;
            }
            p{
               padding-top:20px;
               font-size: 20px;
               padding-bottom: 20px;
            }
            .buy{
               background-color: #fbed3f;
               font-size: 20px;
               color:black;
               padding: 5px 3px 0 3px;
            }
         }   
      }
      .rightcard1{
         width: 60%;
      }
   }
}
}


</style>