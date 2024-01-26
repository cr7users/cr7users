<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Font Awesome CDN  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css"
        integrity="sha512-1PKOgIY59xJ8Co8+NE6FZ+LOAZKjy+KY8iq0G4B3CyeY6wYHN3yt9PW0XpSriVlkMXe40PTKnXrLnZ9+fkDaog=="
        crossorigin="anonymous" />

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">

    
</head>
<body>
    
    
<!--Matn-->
<div class="container">
        <h1>ABOUT<span> IN</span> Joshckar</h1>
        <p>Im Shahryar, <br>I'm 16 years old from the city of Miandoab;<br>Frontent programmer from Shahed Amam Ali school </p>
        <div class="card card0">
            <div class="border">
                <!--icon-->
                <h2>Joshckar</h2>
                <div class="icons">
                    <a href="#"><i class="fab fa-codepen" aria-hidden="true"></i></a>
                    <a href="#"><i class="fab fa-instagram" aria-hidden="true"></i></a>
                    <a href="#"> <i class="fab fa-dribbble" aria-hidden="true"></i></a>
                    <a href="#"><i class="fab fa-twitter" aria-hidden="true"></i></a>
                    <a href="#"><i class="fab fa-facebook" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
     </div>

<style>
        *{
  padding: 0;
  margin: 0;
}
body{
  background: linear-gradient(to top, rgba(0, 0, 0, 0.5)50%, rgba(0, 0, 0, 0.5)50%), url(img/1.jpg);
  background-position: center;
  background-size: cover;
  height: 120vh;
  width: 100%;
}
.container {
  height: 100vh;
  width: 100vw;
  max-height: 800px;
  max-width: 1280px;
  min-height: 600px;
  min-width: 1000px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin: 0 auto;
}

.border {
  height: 369px;
  width: 290px;
  background: transparent;
  border-radius: 10px;
  transition: border 1s;
  position: relative;
}

.border:hover {
  border: 1px solid #fff;
}

.card {
  height: 379px;
  width: 300px;
  background: #808080;
  border-radius: 10px;
  transition: background 0.8s;
  overflow: hidden;
  background: #000;
  box-shadow: 0 70px 63px -60px #000;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}

.card0 {
  background: url("img/23.jpg")
    center center no-repeat;
  background-size: 358px;
}

.card0:hover {
  background: url("img/22.jpg")
    left center no-repeat;
  background-size: 600px;
}

.card0:hover h2 {
  opacity: 1;
}

.card0:hover .fab {
  opacity: 1;
}

h2 {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  color: #fff;
  margin: 20px;
  opacity: 0;
  transition: opacity 1s;
}

.fab {
  opacity: 0;
  transition: opacity 1s;
}

.icons {
  position: absolute;
  fill: #fff;
  color: #fff;
  height: 130px;
  top: 226px;
  width: 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}
.fab.fa-codepen{
  color: #fff;
}
.fab.fa-instagram{
  color: #fff;
}
.fab.fa-dribbble{
  color: #fff;
}
.fab.fa-twitter{
  color: #fff;
}
.fab.fa-facebook{
  color: #fff;
}
.fab.fa-codepen:hover{
  color: #000;
  transition: 1s;
}
.fab.fa-instagram:hover{
  color: red;
  transition: 1s;
}
.fab.fa-dribbble:hover{
  color: orange;
  transition: 1s;
}
.fab.fa-twitter:hover{
  color: #006eff;
  transition: 1s;
}
.fab.fa-facebook:hover{
  color: #002fff;
  transition: 1s;
}


h1{
    color: white;
    margin-top: -350px;
    margin-left: -50px;
    font-family: sans-serif;
}
span{
  color: #ff7200;
}
p{
  position: absolute;
  left: 30px;
  top: 210px;
  color: white;
  padding-bottom: 25px;
  font-family: sans-serif;
  letter-spacing: 1.2px;
  line-height: 30px;
  font-size: 20px;
}
p::selection{
  color: #ff0077;
}
h1::selection{
color: #ff0077;
}
span::selection{
  color: #fff;
}
h2::selection{
  color: #ff0077;
}
@media (max-width:40.625rem){
 body{
  display: flex;
  flex-wrap: wrap;
 }
 .card0{
  display: flex;
  flex-wrap: wrap;
 }
 .card{
  position: absolute;
    top: 341px;
    left: 117px;
    height: 379px;
    width: 300px;
    border-radius: 10px;
    transition: background 0.8s;
    overflow: hidden;
    box-shadow: 0 70px 63px -60px #000;
    display: flex;
    justify-content: center;
    align-items: center;
 }
 h1{    color: white;
  margin-top: -350px;
  margin-left: -11px;
  font-family: sans-serif;
  position: absolute;
  left: 41px;
 }
}
     </style>
</body>
</html>
