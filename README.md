# amazon-clone
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="amazonn.css">
</head>
<style>
    *{
    margin: 0px;
    font-family: Arial;
    border:border-box;
}
.navbar{
    background-color: #0f1111;
    height: 80px;
    width: 100%;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.nav-logo{
    height: 60px;
    width: 100px;
}
.logo{
    background-image: url(logoamazon.jpg);
    background-size: cover;
    width: 165%;
    height: 100%;
    background-color: #0f1111;
}
.border{
    border: 20px solid transparent;
}
.border:hover{
 border: 2px solid white;
}
.frist{
    color: #cccccc;
    font-size: 0.85rem;
    font-size: 110%;
    margin: 10px;
}
.second{
    font-size: 1rem;
    margin: 8px;
}

.nav-seach{
    display: flex;
    justify-content: space-evenly;
    background-color: black;
    width: 620px;
    height: 40px;
    border-radius: 4px;
}

.seach-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius:  4px;
    border-bottom-right-radius: 4px;
    border:none;


}
.nav-seach:hover{
    border:2px solid orange;
}
.search-input{
    width: 500px;
    font-size: 1rem;
}
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.3rem;
    background-color: rgb(246, 179, 8);
    border-top-left-radius:  4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
span{
    font-size: 0.7rem;

}
.nav-second{
    font-size: 0.8;
    font-weight: 700;
}
.nav-card i{
    font-size: 35px;
}
.nav-card{
    font-size: 1.0rem;
    font-weight: 700;
}
.penal{
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}
.pannal-opt p{
    display:inline;
    margin-left: 10px;
}
.pannal-opt{
    width: 70%;
    font-size: 0.8rem;
}
.deals{
    font-size: 0.9rem;
    font-weight: 700;
}
.hero-section{
    background-image: url(amazon123.jpg);
    mix-blend-mode: color-burn;
    background-size: cover;
    height: 350px;
    padding: 0px;

}
.containt{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}
.box{
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}
.box-image{
    height: 300px;
    background-size: cover;
    margin-left: 1rem;
    margin-top: 1rem;
    margin-right: 0.9rem;
}
.box-content {
    margin-left: 12px;
    margin-right: 12px;
}
.box-content p{
    color: #007185;
    margin-left: 12px;
    margin-right:12px;
    margin: 1.3rem;
}
.box-content h2{
    margin-left: 12px;
    margin-right:12px;
}
footer{
    margin-top: 25px;
}
.foot{
    background-color: #37475a;
    color: white;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.9rem;
}
.foot2{
    background-color: #222f3d;
    color: white;
    height: 400px;
    display: flex;
    justify-content: space-evenly;
}
ul{
    margin: 10px;
    padding: 10px;
}
ul a{
    display: block;
    font: 0.85rem;
    margin-top:10px;
    margin-left: 10px;
    color: #dddddd;
}
.foot-panal{
   height: 80px;
   background-color: #3c6591;
   border-top: 0.5px solid white;
   display: flex;
   justify-content: center;
   align-items: center;

}
.atul-log{
    background-image: url(logoamazon.jpg);
    mix-blend-mode: color-burn;
    background-size:cover ;
    height: 50px;
    width: 160px;
}
 .foot4{
    background-color:#3c6591;
    color: white;
    display:flex; 
    height: 100px; 
    justify-content: center; 
    align-items: center;
}
.pages{
    font-size: 0.9rem;
    padding-top: 20px; 
}
.copyright{
    margin: 10px;
    font-size: 0.7rem;  
} 
</style>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>
            </div>
            <div class="nav-address border">
                <p class="frist">Delver to</p>
                <div class="add-icon"><i class="fa-solid fa-location-dot"></i>
                    <p class="second">india</p>
                </div>
            </div>
            <div class="nav-seach">
                <select class="seach-select">
                    <option>All</option>
                </select>
                <input placeholder="Search amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="nav-singin border">
                <p> <span>Hello,sign in</span>
                <p class="nav-second">account & list</p>
            </div>
            <div class="nav-singin border">
                <p> <span>Returns</span>
                <p class="nav-second"> & Orders</p>
            </div>
            <div class="nav-card border">
                <i class="fa-solid fa-cart-shopping"></i>
                cart
            </div>
        </div>
        <div class="penal">
            <div class="panal-all border">
                <i class="fa-solid fa-bars"></i>
                all
            </div>
            <div class="pannal-opt border">
                <p>Today's Deals</p>
                <p>Custmoure Service</p>
                <p>Registery</p>
                <p>Gift nav-cars</p>
                <p>Sell</p>

            </div>
            <div class="deals border">
                shop deals in elctronics
            </div>
        </div>

    </header>

    <div class="hero-section"></div>
    <div class="containt">
        <div class="box1 box">
            <div class="box-conent">
                <h2>Revamp your home in style</h2>
                <div class="box-image" style="background-image: url('box1.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box2 box">
            <div class="box-conent">
                <h2>Starting ₹199 | Amazon Brands & more</h2>
                <div class="box-image" style="background-image: url('box2.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box3 box">
            <div class="box-conent">
                <h2>Appliances for your home | Up to 55% off</h2>
                <div class="box-image" style="background-image: url('box3.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box4 box">
            <div class="box-conent">
                <h2>Automotive essentials | Up to 60% off</h2>
                <div class="box-image" style="background-image: url('box4.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
    </div>
    <div class="containt">
        <div class="box1 box">
            <div class="box-content">
                <h2>Up to 70% off | Home decor products from Emerging busi…</h2>
                <div class="box-image" style="background-image: url('box6tree.jpg')"></div>
                <p>See more</p>
            </div>

        </div>
        <div class="box2 box">
            <div class="box-conent">
                <h2>Up to 65% off | Refurbished products</h2>
                <div class="box-image" style="background-image: url('leptopbox7.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box3 box">
            <div class="box-conent">
                <h2>Up to 50% off | International brands</h2>
                <div class="box-image" style="background-image: url('watch.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box4 box">
            <div class="box-conent">
                <h2>Only at ₹446* | Glass oil dispenser bottle for kitchen</h2>
                <div class="box-image" style="background-image: url('cupbox8.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
    </div>
    <footer>
        <div class="foot">
            back to top
        </div>

        <div class="foot2">
            <ul>
                <a><b>Get to Know Us</b></a>
                <a>About us</a>
                <a>careers</a>
                <a>Press releases</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <a><b>Connect Us </b></a> 
                <a>Facebook</a>
                <a>Twitter</a>
             <a>Instagram</a>
            </ul>
            <ul>
                <A> <b>Money with Us</b></A>
                <a>Sell on Amazon</a>
                <A>Sell under Amazon Accelerator</A>
                <A>Protect and Build Your Brand</A>
                <A>Amazon Global Selling</A>
                <A>Supply to Amazon</A>
                <A>Become an Affiliate</A>
                <A>Fulfilment by Amazon</A>
                <A>Advertise Your Products</A>
                <A>Amazon Pay on Merchants</A>
            </ul>
            <ul>
                <a><b>Let Us Help You</b></a>
                <a>Your Account
                <a>Returns Centre</a>
                <a>Recalls and Product Safety Alerts</a>
                <a>100% Purchase Protection</a>
                <a>Amazon App Download</a>
                <a>Help</a>
            </ul>
        </div>
        <div class="foot-panal">
            <div class="atul-log">
            </div>
        </div>
        <div class="foot4">
            <div class="pages">
                <a> condtion of use & sales</a>
                <a>Privacy Notic</a>
                <a>Your Ads Privacy Choices</a>
                <div class="copy-right">
                    <center>© 1996-2024, Amazon.com, Inc. or its affiliates</center>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
