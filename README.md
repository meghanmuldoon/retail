<!DOCTYPE html>
<html lang="en-US">
    <head>
        <title></title>
        <meta charset="UTF-8">
        <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="stylesheet.css">
        <link href="assets/css/all.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Bowlby+One&family=Open+Sans&display=swap" rel="stylesheet">
        <style>
             /*GENERAL STYLES*/
            html, body {
            margin:0;
            padding:0;
            font-family: serif;
            color:#555;
            }
            img {
                max-width:100%;
                height:auto;
            }
             h2 {
                font-family:'Bowlby One', cursive;
                font-size:2em;
                text-align:center;
                text-transform:uppercase;
                letter-spacing:.2em;
                border-bottom:solid 5px;
                padding-bottom:2px;
            }
            h3 {
                font-family:'Open Sans', sans-serif;
                font-size:.9em;
                text-align:left;
                letter-spacing:2px;
                padding-left: 1em;
            }
            h4 {
                font-family:'Open Sans', sans-serif;
                font-size:.7em;
                text-align:left;
                letter-spacing:2px;
                padding-left: 1em;
            }
           
            
            /*LAYOUT STYLES*/
        
            .hero {
                grid-column:1/13;
               
            }
            section {
                grid-column:1/13;
            }
            .product1 {
                grid-column:1/13;
                background-color: #E1DDE3;
            }
            .product1:hover {
                opacity: 0.5;
            }
            .product2 {
                grid-column:1/13;
                background-color: #E1DDE3;
            }
             .product2:hover {
                opacity: 0.5;
            }
            .product3 {
                grid-column:1/13;
                background-color: #E1DDE3;
            }
            .product3:hover {
                opacity: 0.5;
            }
            .product4 {
                grid-column:1/13;
                background-color: #E1DDE3;
            }
            .product4:hover {
                opacity: 0.5;
            }
            .section2 {
                grid-column:1/13;
            }
            .winter {
                background:url(images/wintercoat1.png);
                background-size: cover;
                background-position: center center;
                height: 500px;
                grid-column:1/13;
                font-family:'Bowlby One', cursive;
                color:#E1DDE3;
                text-align: center;
                letter-spacing:.1em;
                font-size: 23px;
                display:flex;
                justify-content: center;
                align-items: center;
            }
            
            .winter > p {
                background-color: rgba(35, 35, 35, 0.5);
                padding: 12px;
            }
             .winter > p:hover {
                text-decoration: underline;
            }
             .ethically {
                background:url(images/ethically1.jpg);
                background-size:cover;
                background-position: center center;
                height: 500px;
                grid-column:1/13;
                font-family:'Bowlby One', cursive;
                 color:#E1DDE3;
                /* font-family: 'Abril Fatface', cursive;*/
                text-align: center;
                font-size: 23px;
                letter-spacing:.1em;
                display:flex;
                justify-content: center;
                align-items: center;
            }
             .ethically > p {
               background-color: rgba(35, 35, 35, 0.5);
                padding: 12px;
            }
             .ethically > p:hover {
               text-decoration: underline;
            }
            .social1 {
                grid-column:1/13;
                text-align:center;
                letter-spacing:4em;
                padding: 0.5em;
                
            }


@media only screen and (min-width:620px) {
           
            .hero {
                grid-column:1/13;
                grid-row:5/6;
            }
            section {
                grid-column:1/13;
                grid-row:6/7;
            }
            .product1 {
                grid-column:1/7;
                grid-row:7/8;
            }
            .product2 {
                grid-column:7/13;
                grid-row:7/8;
            }
            .product3 {
                grid-column:1/7;
                grid-row:8/9;
            }
            .product4 {
                grid-column:7/13;
                grid-row:8/9;
            }
            .section2 {
                grid-column:1/13;
                grid-row:11/12;
            }
            .winter {
                grid-column:1/13;
                grid-row:12/13;
                
            }
            .ethically {
                grid-column:1/13;
                grid-row:13/14;
            }
            .social1 {
                grid-column:1/13;
                grid-row:14/15;
                text-align:center;
                letter-spacing:2em;
                padding: 1em;
            }
           
                
}
@media only screen and (min-width:900px) {
            header {
                grid-column:1/4;
                grid-row:1/2;
                padding-top: .8em;
            }
            .hero {
                grid-column:1/13;
                grid-row:3/4;
            }
            section {
                grid-column:1/13;
                grid-row:4/5;
            }
            .product1 {
                grid-column:1/4;
                grid-row:5/6;
            }
            .product2 {
                grid-column:4/7;
                grid-row:5/6;
            }
            .product3 {
                grid-column:7/10;
                grid-row:5/6;
            }
            .product4 {
                grid-column:10/13;
                grid-row:5/6;
            }
            .section2 {
                grid-column:1/13;
                grid-row:7/8;
            }
            .winter {
                grid-column:1/7;
                grid-row:8/9;
            }
            .ethically {
                grid-column:7/13;
                grid-row:8/9;
            }
            .social1 {
                grid-column:1/13;
                grid-row:9/10;
                text-align:center;
                letter-spacing:5em;
                padding: 1em;
            }
  
}
                
        </style>
    </head>
    <body>
    <div class="container">
        <header>
        Regalia
        </header>
        
        <div class="logo">
        <img src="images/regalialogo.png" style="width:50%;">
        </div>
        
        <div class="search">
        <i class="fas fa-search fa-lg"> </i> 
        <span class="topnav">
        <input type="text" placeholder="Search..">
            </span>
        </div>
        
        <div class="icons">
        <i class="fas fa-bell fa-2x"></i>
        <i class="fas fa-heart fa-2x"></i>
        <i class="fas fa-user-circle fa-2x"></i>
        <i class="fas fa-shopping-cart fa-2x"></i> 
        </div>
       
    
        
        <nav>
        <ul>
            <li><a href="index.html">home</a></li>
            <li><a href="product1.html">clothing</a></li>
            <li><a href="product2.html">footwear</a></li>
            <li><a href="policy.html">privacy</a></li>
        </ul>
        </nav>
        
        <div class="hero">
        <img src="images/freepeoplepurple1.jpg">
        </div>
         
        <section>
        <h2>Shop Bestsellers</h2>
        </section>
        
        <div class="product1">
        <img src="images/product3.jpeg">
        <h3>down to earth flannel<br></h3>
        <h4>$25.00</h4>
        </div>
        
        <div class="product2">
        <img src="images/freepeoplered.jpeg">
        <h3>comfy lime sweater<br></h3>
        <h4>$35.00</h4>
        </div>
        
        <div class="product3">
        <img src="images/product4.jpeg">
        <h3>magenta flower power turtleneck<br></h3>
        <h4>$30.00</h4>
        </div>
         
        <div class="product4">
        <img src="images/freepeoplepantsred.jpeg">
        <h3>corduroy ulitmate flare<br></h3>
        <h4>$40.00</h4>
        </div>
        
        <div class="section2">
        <h2>Shop Holiday Gifts</h2>
        </div>
        
        <div class="winter">
        <p>WINTER ESSENTIALS</p>
        </div>
        
        <div class="ethically">
        <p>ETHICALLY MADE</p>
        </div>
        
        <div class="social1">
        <i class="fab fa-instagram fa-3x"></i>
        <i class="fab fa-facebook-square fa-3x"></i>
        <i class="fab fa-twitter fa-3x"></i>
        <i class="fab fa-snapchat-square fa-3x"></i>
        </div>
        
        
        <div class="footer1">
            Clothing Co. <br>
            400 Road Street <br>
            Brooklyn, NY <br>
        </div>
            
        <div class="footer2">
            Contact Us <br>
            Returns and Exchanges <br>
            Shipping Policy <br>
        </div>
        
        
        </div>
    </body>
</html>
