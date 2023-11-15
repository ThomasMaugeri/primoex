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
         <div class="leftcard2">
            <img src="https://grace.energy/wp-content/uploads/2023/06/grace-box.jpg" alt="">
         </div>

         <div class="rightcard2">
            <div class="numbercard2">
               <span>2</span>   
            </div>
            <div class="textcard2">
               <h2>antioxidant</h2>
               <span class="awarded">AWARDED BY THE EUROPEAN ANTIOXIDANT INSTITUTE</span>
               <p>The PAOT Score expresses the antioxidant power of a product, measuring its ability to neutralize free radicals. In April 2019, the European Antioxidant Institute (IEA) awarded GRACE a PAOT score of 65.4/g, demonstrating its very high antioxidant power.</p>
               <span class="buy">buy</span>
            </div>
         </div>
      </div>
      
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
            <img src="https://grace.energy/wp-content/uploads/2023/05/grace-bag.jpg" alt="">
         </div> 
      </div>
   </div>
</div>
</template>

<style scoped lang="scss">

.bgpag3{
   background-color: black;
   }
   .pag3{
   width:90%;
   margin: auto;
   padding-top:50px ;
   color:white;
   }   
   .card1{
      width: 100%;
      display:flex;
      .leftcard1{
         width: 60%;
         display: flex;
         .numbercard{
            width: 50px;
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
               width: 40%;
            }
   }
   .card2{
      width: 100%;
      display: flex;
      }
      .leftcard2{
         width: 50%;
      }
      .rightcard2{
         width:50%;
         display:flex; 
         justify-content: flex-end;
         gap: 50px;
         .numbercard2{
          padding: 20px;
          width: 50px;
          
          span{
            border: 2px solid #fbed3f;
            height: 50px;
            width: 50px;
            justify-content: center;
            align-items: center;
            display: flex;
            border-radius: 50%;
            color: #fbed3f;
            font-size: 30px;
          }
         }
      .textcard2{
         .buy{
               background-color: #fbed3f;
               font-size: 20px;
               color:black;
               padding: 5px 3px 0 3px;
            }
            h2{
               padding-top: 20px;
               font-size: 30px;
               padding-bottom: 20px;
            }
         .awarded{
            opacity: .6;
            font-size:20px;
         }
         p{
            padding: 20px 0px;
            font-size: 20px;
         }
      }   
      }
      @media (max-width: 750px) {
         .card1{
            flex-direction: column;
            .rightcard1{
              width: 90%;
              margin: auto;
            }
            .rightcard1 img{
              width: 100%;
            }
         }
         .card2{
            flex-direction:column-reverse;
            .leftcard2{
              width: 90%;
              margin: auto;
            }
            .leftcard2 img{
              width: 100%;
            }
         }
      }

    </style>