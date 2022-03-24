<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="pet home.css">
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
   <section>
    <img src="dog.png" alt="sorry" >
</section> 
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
    padding: 20px 0;
    text-align: center;
}
nav ul{
    background: rgb(8, 8, 8);
    width: 100%;
    margin-top: 10px;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 20px 30px;
    color:rgb(221, 255, 0)
}
 section{
    background:url(dog.png);
    margin-top:10px;
    background-repeat: no-repeat;

}
