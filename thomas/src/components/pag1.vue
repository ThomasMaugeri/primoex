<script >

</script>

<template>
  <div class="header"> 
        <div class="left-header">
            <span>Grace</span>
        </div>  
        <div class="right-header">
            <ul>
                <li class="lang"><a href="">english</a></li>
                <li class="buy"><a href="" class="text-buy">buy</a></li>
                <li class="user"><a href=""><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                </svg></a></li>
                <li class="bag"><a href=""><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-bag" viewBox="0 0 16 16">
  <path d="M8 1a2.5 2.5 0 0 1 2.5 2.5V4h-5v-.5A2.5 2.5 0 0 1 8 1zm3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4h-3.5zM2 5h12v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5z"/>
</svg></a></li>
                <li class="menu"><a href="">menu</a></li>
                <li class="iconmenu"><a href=""><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/>
</svg></a></li>
            </ul>
        </div>  
    </div>

  <div class="main">
    <h1 class="title">Grace</h1>
    <img src="https://grace.energy/wp-content/uploads/2022/03/waves-image-min-2048x866.png" alt="">

   </div>
</template>

<style scoped>
.header{
    display: flex;
    background-color: #999b81;
    color: white;
    padding: 20px 30px 20px 30px;
}
.left-header{
    width: 50%;
    display: flex;
    align-items: center;
    font-size: 30px;
}

.right-header{
    width: 50%;
    display: flex;
    justify-content: flex-end;
    
}
.buy{
    background-color: yellow;
    padding: 0 5px 0 5px;
}
.text-buy{
    color: black;
}
ul{
    display: flex;
    gap: 20px;
    list-style-type: none;
    align-items:center;
}
a{
    text-decoration: none;
    color: white;
}
.main{
    background-color: #999b81;
    display:flex;
    flex-direction: column;
}
img{
    width: 100%;
}
.title{
    text-align: center;
    font-size: 125px;
    color: white;
    padding-top: 200px;
}
</style>
