<script >

</script>

<template>
 <div class="card">
    <div class="left">
        <p>
            5 YEARSOF RESEARCH &DEVELOPMENT
        </p> 
        </div>
        <div class="right">
            <p>CERTIFIED LAB RESULTS 100% NATURAL AND ORGANIC
            73% MORE PROTEIN KETO DIET FRIENDLY
            HIGHEST ANTIOXIDANT RATE100% HIGHER LEVEL OF AMINO ACID</p> 
        </div>
    </div> 
</template>

<style scoped lang="scss">
.card{
    width: 100%;
    display: flex;
    .left{
        width: 50%;
        background-color:yellow;
        display: flex;
        justify-content: center;
        padding: 100px 0;
        p{
            font-size: 30px;
            color: grey;
            text-align: center;
            padding-top: 100px;
        }
    }
    .right{
        width: 50%;
        background-color: aquamarine;
        display: flex;
        padding: 100px 0;
        p{
            font-size: 30px;
            color: white;
            text-align: center;
            padding-top: 70px;
            padding-bottom: 30px;
        }
    }
}


@media (max-width: 770px) {
    .card{
        flex-direction: column;
        .left{
            width: 100%;
        }
        .right{
            width: 100%;
        }
    }

}

</style>