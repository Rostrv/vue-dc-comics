<template>
    <section class="site_footer">
        <div class="container">
           <div class="row">
               <div class="col-6 p-4">
                   <div class="row">
                       <div class="col-3">
                          <h3>dc comics</h3>
                            <ul>
                                <li><a href="">Characters</a></li>
                                <li><a href="">comics</a></li>
                                <li><a href="">movies</a></li>
                                <li><a href="">tv</a></li>
                                <li><a href="">videos</a></li>
                                <li><a href="">games</a></li>
                                <li><a href="">news</a></li>                       
                            </ul>
                       </div>
                       <div class="col-3">
                           <h3>dc</h3>
                            <ul>
                                <li><a href="">terms of use</a></li>
                                <li><a href="">privacy policy</a></li>
                                <li><a href="">ad choices</a></li>
                                <li><a href="">tadvertising</a></li>
                                <li><a href="">jobs</a></li>
                                <li><a href="">subscriptions</a></li>
                                <li><a href="">talent workshop</a></li>
                                <li><a href="">cpsc certificate</a></li>
                                <li><a href="">ratings</a></li>
                                <li><a href="">shop help</a></li>
                                <li><a href="">ncontact us</a></li>                       
                            </ul>

                       </div>
                       <div class="col-3">
                           <h3>sites</h3>
                            <ul>
                                <li><a href="">Characters</a></li>
                                <li><a href="">comics</a></li>
                                <li><a href="">movies</a></li>
                                <li><a href="">tv</a></li>
                                <li><a href="">videos</a></li>                
                            </ul>
                       </div>
                       <div class="col-3">
                           <h3>shop</h3>
                            <ul>
                                <li><a href="">Characters</a></li>
                                <li><a href="">comics</a></li>   
                            </ul>
                       </div>

                   </div>
               </div>
               <div class="col-6 logo">
                   <img src="@/assets/img/dc-logo-bg.png" alt="">
               </div>
           </div>
        </div>
        <div class="footer-bottom">
            <div class="container bottom">
                <button>
                    SIGN UP NOW!
                </button>

            </div>

        </div>
        
    </section>
</template>

<style lang="scss" scoped>
.site_footer {
    background-image: url("@/assets/img/footer-bg.jpg");
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;  
    
    
    & .container{
        height: 400px;
    }

    & .logo{
        position: relative;
        z-index: 1;
        top: -100px;
    }

    & .col-3{
        text-align: start;
    }

    & ul{
        padding:0;
    }

    & h3{
        color: white;
        text-transform: uppercase;
        font-size: 20px;
        font-weight: bold;
    }
    
    & a{
        text-decoration: none;
        color: lightslategrey;
    }

    & a:hover{
        color: white;
    }
    
    & .footer-bottom{
        background-color: rgb(58, 56, 56);
        position: relative;
        z-index: 1;
    }

    & .bottom{
        padding: 0;
        height: 150px;
        display: flex;
        align-items:center;
        justify-content: space-between;
    }

    & button{
        color: white;
        font-weight: bold;
        background-color:transparent;
        border: 2px solid #0282f9;
        padding: 1rem;
    }
}








</style>