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
                                <li><a href="">Comics</a></li>
                                <li><a href="">Movies</a></li>
                                <li><a href="">Tv</a></li>
                                <li><a href="">Videos</a></li>
                                <li><a href="">Games</a></li>
                                <li><a href="">News</a></li>                       
                            </ul>
                       </div>
                       <div class="col-3">
                           <h3>dc</h3>
                            <ul>
                                <li><a href="">Terms of use</a></li>
                                <li><a href="">Privacy policy</a></li>
                                <li><a href="">Add choices</a></li>
                                <li><a href="">Advertising</a></li>
                                <li><a href="">Jobs</a></li>
                                <li><a href="">Subscriptions</a></li>
                                <li><a href="">Talent workshop</a></li>
                                <li><a href="">Cpsc certificate</a></li>
                                <li><a href="">Ratings</a></li>
                                <li><a href="">Shop help</a></li>
                                <li><a href="">Contact us</a></li>                       
                            </ul>

                       </div>
                       <div class="col-3">
                           <h3>sites</h3>
                            <ul>
                                <li><a href="">DC</a></li>
                                <li><a href="">Mad Magazine</a></li>
                                <li><a href="">DC Kids</a></li>
                                <li><a href="">DC Univers</a></li>
                                <li><a href="">DC Power Visa</a></li>                
                            </ul>
                       </div>
                       <div class="col-3">
                           <h3>shop</h3>
                            <ul>
                                <li><a href="">Shop DC</a></li>
                                <li><a href="">Shop DC Collectibles</a></li>   
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
                <div class="right d-flex align-items-center">
                    <h4>follow us</h4>
                    <ul class=" icons d-flex align-items-center m-0">
                        <li><a href=""><img src="@/assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href=""><img src="@/assets/img/footer-twitter.png" alt=""></a></li>
                        <li><a href=""><img src="@/assets/img/footer-youtube.png" alt=""></a></li>
                        <li><a href=""><img src="@/assets/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href=""><img src="@/assets/img/footer-periscope.png" alt=""></a></li>

                    </ul>
                </div>
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

    & h4{
        color:#0282f9;
        text-transform: uppercase;
        margin: 0;
        margin-right: 20px;
        font-weight: bold;
    }

    & .icons li{
        margin-right: 20px;
    }
}

</style>