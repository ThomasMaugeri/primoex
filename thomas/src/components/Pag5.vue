<script >

</script>

<template>
    <div class="Pag5">
        <div class="main">
            <h1>3 metabolic boosters</h1>
            <div class="first">
                <h2>AMINO ACIDS</h2>
                <span>+</span>
            </div>
            <div class="second">
                <h2>ANTIOXIDANT</h2>
                <span>+</span>
            </div>
            <div class="third">
                <h2>PROTEIN</h2>
                <span>+</span>
            </div>
        </div>
    </div>

</template>

<style scoped lang="scss">
.Pag5{
    background-color:black;
    color: white;
    .main{
        width: 90%;
        margin: auto;
    }
    h1{
       padding: 50px 50px;
    }
    .first{
        border-top: 2px solid white;
        border-bottom: 2px solid white;
        padding: 20px;  
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    .second, .third{
        border-bottom: 2px solid white;
        padding: 20px;
          display:flex;
          align-items: center;
        justify-content: space-between;
    }

    span{
        font-size: 50px;
        
    }
}

</style>