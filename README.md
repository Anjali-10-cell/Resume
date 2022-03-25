<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="pet.css">
</head>
<body>
   <div class="header">
       <nav>
        <ul>
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Fitness</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
       </nav>
   </div>
   <section class="my_img">
   </section> 
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="cat.png" alt="First slide" width="50%" height="50%" <p>Hii</p>>
      </div>
      <div class="carousel-item">
        <img src="doa and cat.jpg" alt="Second slide" width="50%" height="50%">
      </div>
      <div class="carousel-item">
        <img src="Dog.png" alt="Third slide" width="50%" height="50%">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</body>
</html>




///// csss
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Courier New', Courier, monospace;
}

.header{
    width: 100%;
    height: 100%;
    background-size: cover;

}
nav{
    width: 100%;
    /*padding: 20px 0;*/
    text-align: center;
}
nav ul{
    background:gray;
    width: 100%;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 20px 30px;
    color:rgb(105, 128, 0)
}
section.my_img{
    height:100vh;
    width: 100%;
    background:url(Dog.png);
    background-size: cover;
    margin-top:10px;
    background-repeat: no-repeat;

}


