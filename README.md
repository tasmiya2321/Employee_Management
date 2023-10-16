<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME</title>
    <script src="https://kit.fontawesome.com/bc0ac06df1.js" crossorigin="anonymous"></script>
    <style>
        * {
            
            box-sizing:border-box;
            padding: 0;
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
    body{
        background-color: rgb(247, 241, 233);
    }

.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
  margin-top: 3%;
  border-radius: 2px;
  margin-left: 30%;
}


.mySlides {
  display: none;
}


.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}


.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}


.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 1px;
  width: 1px;
  margin: 0 2px;
  background-color:none;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}


.fade {
  animation-name: fade;
  animation-duration: 5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
.footer{
    background-color: bisque;
    height: 150px;
}








.content {
    text-align: center;
    padding: 50px;
}

h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

p {
    font-size: 18px;
}

.unique-footer {
    background-color: #201f1e;
    color: #fff;
    padding: 20px 0;
    margin-top: 20%;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 800px;
    margin: 0 auto;
    padding: 0 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    background-image: url(./cf_logo.png);
    width: 30%;
}

.footer-links ul {
    list-style: none;
    padding: 0;
}

.footer-links ul li {
    display: inline;
    margin-right: 20px;
}

.footer-links a {
    text-decoration: none;
    color: #fff;
    font-size: 16px;
    flex-direction: column;
}

.footer-text {
    text-align: center;
    margin-top: 10px;
    font-size: 14px;
}


@media (max-width: 600px) {
    .footer-content {
        flex-direction: column;
    }
}

center{
    font-size: 25px;
    margin-top: 2%;

    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}


.dropbtn {
    background-color: rgb(247, 241, 233);
    color: rgb(17, 17, 17);
    font-size: 16px;
    border: none;
    cursor: pointer;
    padding: 10px;
    margin-left: 85%;
}


.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    margin-left: 80%;
}


.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}


.dropdown-content a:hover {
    background-color: #f1f1f1;
}


.dropdown:hover .dropdown-content {
    display: block;
}



.card{
  width: 25%;
  height: 30%;
  background-color: rgb(233, 166, 21);
  margin-top: -38%;
  margin-left: 1.5%;
  border-radius: 3px;
  border: 2px solid rgb(10, 10, 10);
  
}
.card,h3{
  margin-left: 60px;
}
.card.p{
  margin-left: 100px;
}

.footer-text{
  margin-right:80%;
  list-style-type: none;
  margin-top: -2%;


}
.footer-text{
     
       margin-left: 5%;
       font-size: 8px;
}
.sas{
  font-size: 10px;
}
.map{
  margin-left: 23%;
  
}
 

    </style>
</head>
<body>
    
    <center>Home</center>
    <div class="dropdown">
        <button class="dropbtn">Jimmy Cheriyan<i class="fa-solid fa-circle-user fa-2xl" style="color: #5c626a;"></i></button>
        <div class="dropdown-content">
            <a href="#"><i class="fa-solid fa-key"></i>Change Password</a>
            <a href="#"><i class="fa-solid fa-right-from-bracket"></i>Log out</a>
          
        </div>
    </div>
     

<div class="slideshow-container">
   
   
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./scifi-background-for-pc-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./cristiano-ronaldo-4k-hd-pc-download-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./forest-4k-background-for-pc-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./lucifer-4k-pc-background-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./nature-full-size-desktop-7680x4320-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./pc-game-ps4-hellblade-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>
  
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="./neon-keyboards-computer-pc-gaming-wallpaper-preview.jpg" style="width:100%">
      <div class="text"></div>
    </div>
  
    <!-- Next and previous buttons -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
  <br>
  
  <!-- The dots/circles -->
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>


  <div class="card">
    <h3>Jimmy Cheriyan</h3><br><br>
    <p>
       Jimmy Cheriyan, a tenacious force, propelled an NGO through sheer determination. His unwavering commitment to the cause ignited hope in countless hearts, forging a path to change. Jimmy's indomitable spirit continues to inspire and drive transformative impact.
    </p>
</div>
  
<footer class="unique-footer">
    <div class="footer-content">
        <div class="logo"></div>
        <div class="footer-links">
            <ul>
                <li><a href="https://in.linkedin.com/company/creating-futures
                    "><i class="fa-brands fa-linkedin fa-2xl" style="color: #1461e6;"></i></a></li>
                <li><a href="https://www.facebook.com/EducationtoEmployability/"><i class="fa-brands fa-facebook fa-2xl" style="color: #105ada;"></i></a></li>
                <li><a href="https://www.youtube.com/@creatingfutures3433"><i class="fa-brands fa-youtube fa-2xl" style="color: #e70d0d;"></i></a></li>
                <li><a href="https://www.instagram.com/i_am_creating_futures/?hl=en"><i class="fa-brands fa-instagram fa-2xl" style="color: #ee77a7;"></i></a></li>
            </ul>
        </div>
    </div>
    <div class="footer-text">
        <li class="saa"></i></li>
        <p class="sas"><i class="fa-solid fa-location-dot fa-2xl" style="color: #c2c7d1;"></i>
         <br><br> No.40, 2nd Main Rd, 3rd Cross Rd, Ambedkar Nagar, Coffee Board Colony, Bengaluru, Karnataka 
         
        </p>
        <p class="sas"> Phone: 098451 32192</p>
        <p class="sas">Pin code : 560045</p>
    </div>
    <div class="map">
      
     <p class=""><i class="fa-solid fa-map-location-dot"></i> Creating Futures</p>
    </div>
</footer>






<script>
    let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 10000); 
}
  </script>
</body>
</html>
