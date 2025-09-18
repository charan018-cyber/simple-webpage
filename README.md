[simplotel.html](https://github.com/user-attachments/files/22404364/simplotel.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header class="topbar">
        <nav class="nav ">
            <div class="navcont">
            <a href="#home">Home</a>
            <a href="#order">Order</a>
            <a href="#food">Food</a>
            <a href="#restaurant">Restaurant</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#">Contact us </a>
            </div>
            <img src="menu-bar.png" alt="menue icon" width="40px" height="40px">
        </nav>
    </header>
    <section class="maindiv">
        <div class="inner1">
        <h1> LOREM IPSUM</h1>
        <br>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vivamus id est vitae dolor rhoncus tristique. Maecenas metus quam, rhoncus euismod lorem in, sollicitudin viverra eros. Donec dictum luctus quam ut tristique. Curabitur nec faucibus purus. Quisque congue sem nec justo mollis, in tincidunt erat pretium. Sed pulvinar, massa ac porta viverra.</p>
        <br>
        <a class="btn1" href="#button">Click Me</a>
        </div>
        <div class="inner2">
            <img src="pexels-robin-stickel-70497.jpg">
        </div>
    </section>
    <section class="gallery">
        <div class="imag">
            <div class="col">
            <img src="pexels-rachel-claire-6752433.jpg" alt="nightlight">
            <img src="pexels-eva-bronzini-6141651.jpg" alt="street">
            </div>
            <div class="col1">
            <img src="pexels-mister-mister-3434523.jpg" alt="food">
            </div>
        </div>
        <div class="text">
            <small>LOREM IPSUM</small>
            <h2>LOREM, IPSUM DOLOR.</h2>
            <a class="btn2" href="#">Click <img src="icons8-arrow-30.png" alt="arrow"></a>
        </div>
    </section>

</body>
<style>
    :root{
        --pink:#ffb3b3;
        --peach:#ffc9a9;
        --yellow:#fff1a6;
        --coral:#ff8f87;
        --ink:#222;
    }
   *{
    box-sizing: border-box;
   }
   html,body{
    margin: 0px;
   }
  
   /*header*/
   .topbar{
    background:#f2807a;
    padding: 4px 20px;
    
   }
   .nav {
    max-width: 100%;
    margin: 0px auto;
    display: flex;
    align-items: center;
    padding-left: 140px ;
    gap: 40px;
  
   }
   .navcont a{
    text-decoration: none;
    font-size:25px;
    align-items: center;
    font-family:'Times New Roman', Times, serif;
    padding-left: 50px ;
    color: black;
   }
   /* maindiv */
   .maindiv{
    width: 100%;
    height: 600px;
    display:flex;
   }
   .inner1{
    width: 50%;
    padding: 60px;
    justify-content: center;
    flex-direction: column;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg,var(--yellow),var(--pink));
   }
   .inner1 h1{
    font-size: 48px;
    letter-spacing: 3px;
   
   }
   .inner1 p{
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 30px;
    
   }
   .btn1{
    display:inline-block;
    background: #f2807a;
    color: white;
    text-decoration: none;
    padding: 12px 40px;
    font-size: 10px;
   }
   .inner2{
     width: 50%;
   }
   .inner2 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
   }
   /*second page */
   .gallery {
    display: flex;
    width: 100%;
    height: 600px;
    background: linear-gradient(135deg, var(--yellow), var(--pink), #f6a8ff);
    padding: 60px;
    box-sizing: border-box;
    gap: 40px;
}

.imag {
    margin-top: 30px;
    width: 50%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}

.col {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.col img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
}
.col1 img{
    width: 100%;
    height: 420px;
    object-fit: cover;
    display: block;
}

.text {
    width: 50%;
    height: 200px;
    display: flex;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    justify-content: center;
    background: #f2807a;
    padding: 20px;
    max-width: 400px;
    margin-top: 110px;
    color: #000;
    flex-direction: column;
}

.text small {
    font-size: 10px;
    letter-spacing: 2px;
    font-weight: bold;
}

.text h2 {
    font-size: 36px;
    font-weight: 900;
    line-height: 1.2;
    
}

.btn2 {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    color: #000;
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
}

.btn2 img {
    width: 20px;
    height: 20px;
}

  

</style>
</html>
