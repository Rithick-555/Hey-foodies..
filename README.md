
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title class="title">Hey foodies..!</title>
<link rel="icon" type="images/x-icon" href="Restaurant/restaurant (1).png">
<style>
*{
margin: 0 0;
padding: 0 0;
font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.title{
    font-style: italic;
}
.container{
width: 80%;
margin:0 auto;
padding: 0.1%; 
}
.img-responsive{
width:fit-content;
}
.text-align{
text-align: right;
font-size: 150%;
}
.text-center{
text-align: left;
}
.logo{
width: 0.5%;
height: 0%;
float:left;
}
.menu {
list-style-type: none;
}
.menu li{
display: inline;
padding: 1%;
font-weight: bolder;
}
.clearfix{
clear: both;
float: none;
}
.menu{
line-height: 150px;
}
a{
color: #ff6b81 ;
text-decoration:underline;
}
a:hover{
color: #ff4757;
}
.food-search{
background-image: url("Restaurant/Background.jpg");
background-size: fixed;
background-position: center;
padding: 10% 0;
}
.food-search input[type="search"]{
width: 50%;
padding: 1%;
font-size: 1rem;
border-radius: 10px;
}
.btn{
padding: 1%;
border: none;
font-size: 1rem;
border-radius: 10px;
}
.btn-primary{
background-color: #df8013;
color: aliceblue;
cursor: pointer;
}
.btn-primary:hover{
background-color: aqua;
}
.categories{
background-color: beige;
padding: 2%;
text-decoration: underline;
}
.text-center{
text-align: center;
color: white;
font-size: 20px;
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
.box{
width: 30%;
float: left;
margin: 1%;
}
.box:hover .overlay{
    opacity: 1;
}
.float-container{
position: relative;
width:30%;
}
.float-text{
position: absolute;
bottom: 50px;
left: 30%;
}
.text-white{
color: black;
font-style: italic;
}
h2{
font-size: 2rem;
margin: 2%;
}
.img-curve{
border-radius: 40px;
display: block;
width: 90%;
height: auto;
}
.overlay{
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color:gray;
}
.food-menubox{
width: 40%;
margin: 1%;
float: left;
background-color: white;
border-radius: 10px;
padding: 3%;
}
.food-menu{
background-color:grey;
padding: 10% 0;
}
.food-menu-img{
width:fit-content;
float: left;
}
.food-menu-desc{
width: 70%;
float: center;
margin-left:29%;
padding: 2%;
}
.food-price{
font-size: 1.5rem;
padding: 1%;
}
.food-detail{
font-size: 1rem;
color: #ff4757;
}
h4{
font-style: italic;
padding-bottom: 2%;
}
.social ul{
list-style-type: none;
}
.social{
    padding: 2%;
}
.social ul li{
display: inline;
padding: 1%;
}
.navbar{
background-color: none;
}
.footer{
background-color: #f5e3e4;
}
.text{
    text-align: center;
    padding-top: 10%;
    padding-bottom:5%;
    text-decoration: underline;
    background-color: aquamarine;
}
.text-pri{
    text-align: center;
  
    font:250% 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ;
    padding-bottom: 5%;
    color: #df8013;
    background-color: aquamarine;
}

.text-footer{
    text-align: center;
}
.underline{
    text-decoration: underline;
}

</style>
</head>
<body>
<section class="navbar">
<div class="container">
<div class="logo">
<img src="Restaurant/LOGO.png" alt="Restaurant Logo">
</div>
<div class="menu text-align">
<li>
<a href="#">Home</a>
</li>
<li>
<a href="#">About</a>
</li>
<li>
<a href="#">Foods</a>
</li>
<li>
<a href="#">Contact</a>
</li>
</div>
</div>
<div class="clearfix"></div>
</section>
<section class="food-search text-footer">
<div class="container">
<form action="">
<input type="search" name="search" placeholder="Search for food..">
<input type="submit" name="submit" value="Search" class="btn btn-primary">
</form>
</div>
</section>
<h1 class="text">About</h1>
<p class="text-pri">Here we are providing very fresh food and hygenic food only,And the price of oru food is budgetable as much as taste is very good as per you want.</p>
<section class="categories">
<div class="container">
<h2 class="text-footer">Categories</h2>
<a href="#">
<div class="box float-container">
<img src="RESTAURANT/Food 1.jpg" alt="Chicken" class="img-responsive img-curve">
<div class="overlay">
<h2 class="float-text text-white">NON VEG</h2>
</div>
</div>
</a>
<a href="#">
<div class="box float-container">
<img src="Restaurant/food 2.jpg" alt="Chicken" class="img-responsive img-curve">
<div class="overlay">
<h2 class="float-text text-white">PIZZA</h2>
</div>
</div>
</a>
<a href="#">
<div class="box float-container">
<img src="Restaurant/food 3.jpg" alt="Chicken" class="img-responsive img-curve">
<div class="overlay">
<h2 class="float-text text-white">BURGER</h2>
</div>
</div>
</a>
<div class="clearfix"></div>
</div>
</section>
<section class="food-menu">
<div class="container">
<h2 class="text-footer underline">Explore Foods</h2>
<div class="food-menubox">
<div class="food-menu-img">
<img src="Restaurant/food 4.jpg" alt="Burger" class="img-responsive img-curve" >
</div>
<div class="food-menu-desc">
<h4>Burger</h4>
<p class="food-price">Rs.200</p>
<p class="food-detail">
Made with Indian<br>style...
</p><br>
<a href="#" class="btn btn-primary">ORDER NOW!!</a>
</div>
<div class="clearfix"></div>
</div>
<div class="food-menubox">
<div class="food-menu-img">
<img src="Restaurant/food 4.jpg" alt="Drink" class="img-responsive img-curve" >
</div>
<div class="food-menu-desc">
<h4>Drink</h4>
<p class="food-price">Rs.250</p>
<p class="food-detail">
Made with Cold and<br>Indian style...
</p><br>
<a href="#" class="btn btn-primary">ORDER NOW!!</a>
</div>
<div class="clearfix"></div>
</div>
<div class="food-menubox">
<div class="food-menu-img">
<img src="Restaurant/food 7.jpg" alt="Naan" class="img-responsive img-curve" >
</div>
<div class="food-menu-desc">
<h4 >Naan</h4>
<p class="food-price">Rs.300</p>
<p class="food-detail">
Made with cheese and<br>Chicken...
</p><br>
<a href="#" class="btn btn-primary">ORDER NOW!!</a>
</div>
<div class="clearfix"></div>
</div>
<div class="food-menubox">
<div class="food-menu-img">
<img src="Restaurant/food 8.jpg" alt="Veg" class="img-responsive img-curve" >
</div>
<div class="food-menu-desc">
<h4>Veg</h4>
<p class="food-price">Rs.400</p>
<p class="food-detail">
Made with fresh<br>vegetables...
</p><br>
<a href="#" class="btn btn-primary">ORDER NOW!!</a>
</div>
<div class="clearfix"></div>
</div>
<div class="clearfix"></div>
</div>
</section>
<section class="social">
<div class="container text-footer">
<ul>
<li>
<a href="#"><img src="https://img.icons8.com/fluent/48/000000/instagram-new.png"/></a>
</li>
<li>
<a href="#"><img src="https://img.icons8.com/fluent/50/000000/facebook-new.png"/></a>
</li>
</ul>
</div>
</section>
<section class="footer">
<div class="container text-footer">
<p>All rights reserved. Designed By <a href="#">Rithick</a></p>
</div>
</section>
</body>
</html>
