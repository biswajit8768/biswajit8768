#biswajit8768
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dream Car</title>
    <!-- font awesome cdn link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
    <!--  custom css file link  -->
    <link rel="stylesheet" href="style.css">



</head>
<body>
     
<!--header section starts-->

<header class="header">

    <div id="menu-btn" class="fas fa-bars"></div>
    <a href="#" class="logo"> <span>Dream</span>Car</a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#vehicles">vehicles</a>
        <a href="#services">services</a>
        <a href="#features">features</a>
        <a href="#reviews">reviews</a>
        <a href="#contact">contact</a>
    </nav>
     
    <div id="login-btn">
        <button class="btn">login/signup</button>
        <i class="far fa-user"></i>
    </div>


</header>

<!--header section goes here -->

<!--login form-->

<div class="login-form-container">

    <span class="fas fa-times" id="close-login-form"></span>
    <form action="http://localhost:3000/signup" method="post">
        <h3>User login</h3>
        <input type="email" placeholder="email" class="box">
        <input type="password" placeholder="password" class="box">
        <p>forget your password<a href="#">click here</a></p>
        <input type="submit" value="login now" class="btn">
        <p>or login with</p>
        <div class="buttons">
            <a href="#" class="btn">google</a>
            <a href="#" class="btn">facebook</a>
        </div>
        <p>don't have an account<a href="#">create one</a></p>
    </form>
</div>



<!--home section starts here -->
<section class="home" id="home">
    <h1 class="home-parallax" data-speed="-2"> find your dream car</h1>
    <img class="home=parallax" data-speed="5" src="Image/home-img3.png" alt="">
    <a href="#" class="btn home-parallax" data-speed="7">explore cars</a>



</section>

<!--home section ends-->

<!--icons section here-->
<section class="icons-container">
   
   
    <div class="icons">
        <i class=""fas fa-home"></i>
        <div class="content">
            <h3>100+</h3>
            <p>branches</p>
        </div>
    </div>

    <div class="icons">
        <i class="fas fa-car"></i>
        <div class="content">
            <h3>4000+</h3>
            <p>cars sold</p>
        </div>
    </div>

    <div class="icons">
        <i class="fas fa-users"></i>
        <div class="content">
            <h3>500+</h3>
            <p>happy clients</p>
        </div>
    </div>

    <div class="icons">
        <i class="fas fa-users"></i>
        <div class="content">
            <h3>800+</h3>
            <p>new cars</p>
        </div>
    </div>
</section>

<!--icons section ends here -->
<section class="vehicles" id="vehicles">
    <h1 class="heading"> popular <span>vehicles</span> </h1>
    <div class="vehicles-slider">
        <div class="wrapper">
            <div class="box">
                <img src="Image/home-img1.png" alt="">
                <div class="content">
                    <h3>new model</h3>
                    <div class="price"><span>price: </span> 6,00,000 Inr</div>
                    <p>
                         new
                         <span class="fas fa-circle"></span> 2021
                         <span class="fas fa-circle"></span> automatic
                         <span class="fas fa-circle"></span> petrol
                         <span class="fas fa-circle"></span> 183mph
                    </p>
                    <a href="#" class="btn">check out</a>
                </div>

                <div class="box">
                    <img src="Image/home-img2.png" alt="">
                    <div class="content">
                        <h3>new model</h3>
                        <div class="price"><span>price: </span> 6,00,000 Inr</div>
                        <p>
                             new
                             <span class="fas fa-circle"></span> 2021
                             <span class="fas fa-circle"></span> automatic
                             <span class="fas fa-circle"></span> petrol
                             <span class="fas fa-circle"></span> 183mph
                        </p>
                        <a href="#" class="btn">check out</a>
                    </div>

                    <div class="box">
                    <img src="Image/home-img.png" alt="">
                    <div class="content">
                        <h3>new model</h3>
                        <div class="price"><span>price: </span> 6,00,000 Inr</div>
                        <p>
                             new
                             <span class="fas fa-circle"></span> 2021
                             <span class="fas fa-circle"></span> automatic
                             <span class="fas fa-circle"></span> petrol
                             <span class="fas fa-circle"></span> 183mph
                        </p>
                        <a href="#" class="btn">check out</a>
                    </div>

                    <div class="box">
                        <img src="Image/home-img4.png" alt="">
                        <div class="content">
                            <h3>new model</h3>
                            <div class="price"><span>price: </span> 6,00,000 Inr</div>
                            <p>
                                 new
                                 <span class="fas fa-circle"></span> 2021
                                 <span class="fas fa-circle"></span> automatic
                                 <span class="fas fa-circle"></span> petrol
                                 <span class="fas fa-circle"></span> 183mph
                            </p>
                            <a href="#" class="btn">check out</a>
                        </div>
            </div>
        </div>
    </div>
</section>










    <script src="script.js"></script>     
</body>
</html>
