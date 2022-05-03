<template>
    <section class="middle">
        <div class="container">
            <ul class="p-0 m-0">
                <li> <a href=""> <img src="@/assets/img/buy-comics-digital-comics.png" alt=""> digital comics</a></li>
                <li> <a href=""> <img src="@/assets/img/buy-comics-merchandise.png" alt="">dc merchandise</a> </li>
                <li> <a href=""> <img src="@/assets/img/buy-comics-shop-locator.png" alt="">subscription</a> </li>
                <li> <a href=""> <img src="@/assets/img/buy-comics-subscriptions.png" alt="">comic shop locator</a> </li>
                <li> <a href=""> <img src="@/assets/img/buy-dc-power-visa.svg" alt="">dc power visa</a> </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>

.middle{
    background-color:#0282f9;
    padding: 1rem 0;
    
    
    

    & img{
        width:50px;
        margin-right: 15px;
    }

    & .container{
        height: 150px;
        display: flex;
        flex-direction: column;
        justify-content:center;
        margin: auto;
        
        
    }

    & ul{
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        list-style: none;
        
    }

    & a{
        text-decoration: none;
        color: white;
        text-transform: uppercase;
        
        
    }
}
</style>