<template>
  <div class="home">
    <nav class="navbar navbar-light fixed-top bg-light">
       <a class="navbar-brand" href="#">
           <img src="../assets/dexter.png" width="50" height="50" alt="Dexter">Dexter Dojo
       </a>
       <form class="form-inline">
         <div class="inset">
           <img src="../assets/profile.png">
         </div>
         <div class="dropdown px-3">
     <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    User Name
     </button>
     <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
       <a class="dropdown-item" href="#">Setting</a>
       <a class="dropdown-item" href="#">Logout</a>
     </div>
   </div>
    </form>
   </nav>
    <div class="container">
      <div class="row">
        <div class="col-sm-4" style="margin-top:150px;">
    <div class="card card1 hvr-grow-shadow">
      <div class="card-body">
      <!-- <div class="user-buttons d-flex justify-content-end">
  <a class="fa fa-cog" aria-hidden="true"></a>
</div> -->
        <div class="row">
          <div style="margin-top:5px;">
        <img src="../assets/university.png" width="80" height="80 " alt="university">
</div>
<div>
    <h4 class="text-center" style="color:teal;">Anna University</h4>
      	<div class="float-left px-2 text-center" style="font-size:20px;color:red;">
      		123<br>Staff
        </div>
        <div class="float-left px-2 text-center"  style="font-size:20px;color:blue;">
        200<br>Student
      </div>
      <div class="float-left px-2 text-center"  style="font-size:20px;color:green;">
      58<br>Parent
   </div>
</div>
</div>
</div>
<div>
<!-- <button class="btn btn1"><i class="fa fa-comment"></i></button>
<span class="badge badge-notify">5</span>
<button class="btn btn2"><i class="fa fa-heart"></i></button>
<span class="badge badge-notify">3</span>
<button class="btn btn3"><i class="fa fa-newspaper-o"></i></button>
<span class="badge badge-notify">1</span> -->
<a href="#" class="alarm-badge float-right px-3" data-badge="12" >
  <button class="btn button1">
    <i class="fa fa-comment"></i>
  </button>
</a>
<a href="#" class="alarm-badge float-right px-3" data-badge="25" >
  <button class="btn button2">
    <i class="fa fa-heart"></i>
  </button>
</a>
<a href="#" class="alarm-badge float-right px-3" data-badge="51" >
  <button class="btn button3">
    <i class="fa fa-newspaper-o"></i>
  </button>
</a>
</div>
<!-- <ul class="social-network social-circle">
                        <li data-couner="3"><a href="#" class="icoRss" title="Rss"><i class="fa fa-rss"></i></a></li>
                        <li><a href="#" class="icoFacebook" title="Facebook"><i class="fa fa-facebook"></i></a></li>
                        <li><a href="#" class="icoTwitter" title="Twitter"><i class="fa fa-twitter"></i></a></li>
                        <li><a href="#" class="icoGoogle" title="Google +"><i class="fa fa-google-plus"></i></a></li>
                        <li><a href="#" class="icoLinkedin" title="Linkedin"><i class="fa fa-linkedin"></i></a></li>
                    </ul> <span class="app-icon fa-stack fa-2x" data-count="19">
                    	<i class="fa fa-square fa-stack-2x"></i>
                    	<i class="fa fa-bell fa-stack-1x fa-inverse"></i>
                    </span> -->
</div>
</div>
<div class="col-md-6" style="margin-top:150px;">
<div class="card card1 hvr-grow-shadow float-left px-2 text-center">
  <div class="card-body text-center">
    <a href="#" class="float text-center">
    <i class="fa fa-plus icon-float"></i>
    </a>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</template>
<script>
export default{

}
</script>

<style>
body{
  background-color:	#F0EFEC;
}
.nav {
  height:70px;
  width: 100%;
  background-color:#ffffff;
  position: relative;
}
.inset {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  box-shadow:
    inset 0 0 0 2px rgba(255,255,255,0.6),
    0 1px 1px rgba(0,0,0,0.1);
  background-color: transparent !important;
  z-index: 999;
}

.inset img {
  border-radius: inherit;
  width: inherit;
  height: inherit;
  display: block;
  position: relative;
  z-index: 998;
}
.btn{
  fill: #fff;
  background: #fff;
}
.btn-1{
        border-radius:20px;
        box-shadow: 2px 2px;
        font-size: 18px;
        color: #000;
        margin: auto;
}
.hvr-grow-shadow {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  -moz-osx-font-smoothing: grayscale;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
}
.hvr-grow-shadow:hover, .hvr-grow-shadow:focus, .hvr-grow-shadow:active {
  box-shadow: 0 10px 10px -10px rgba(0, 0, 0, 0.5);
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}

.alarm-badge {
  font-family: 'Helvetica Neue';
  position: relative;
  font-size:2em;
  color: #333;
  transition: all .2s ease-in-out;
}
.alarm-badge[data-badge]:after {
  content: attr(data-badge);
  position: absolute;
  top: -5px;
  left: 60%;
  font-size: .4em;
  font-weight: bold;
  background:red;
  color: #fff;
  text-align: center;
  border-radius:50%;
  padding: 3px 5px;
}
.button1{
  position:224px 247px;
  border-radius:60%;
  background-color:#3DC0F9;
  margin-top:-15px;
}
.button2 {
  border-radius:60%;
  background-color:#ff69b4;
    margin-top:-15px;
}
.button3{
  border-radius:60%;
  background-color:#FFFF66 ;
  margin-top:-15px;
}
.card1{
  border-radius:5px;
  box-shadow:1px 2px;
  width:305px;
  height:155px;
}
/* .float{
	position:absolute;
	width:60px;
	height:60px;
	background-color:#0C9;
	color:#FFF;
	border-radius:50px;
	box-shadow: 2px 2px 3px #999;
} */
.icon-float{
  font-size:33px;
	margin-top:45px;
}
/*
.btn-floating i {
    display: inline-block;
    width: inherit;
    text-align: center;
    color: #fff;
}
.btn-floating i {
    font-size: 1.25rem;
    line-height: 47px;
}

ul.social-network {
	list-style: none;
	display: inline;
	margin-left:0 !important;
	padding: 0;
}
ul.social-network li {
	display: inline;
	margin: 0 5px;
}

.social-network a.icoRss:hover {
	background-color: #F56505;
}
.social-network a.icoFacebook:hover {
	background-color:#3B5998;
}
.social-network a.icoTwitter:hover {
	background-color:#33ccff;
}
.social-network a.icoGoogle:hover {
	background-color:#BD3518;
}
.social-network a.icoVimeo:hover {
	background-color:#0590B8;
}
.social-network a.icoLinkedin:hover {
	background-color:#007bb7;
}
.social-network a.icoRss:hover i, .social-network a.icoFacebook:hover i, .social-network a.icoTwitter:hover i,
.social-network a.icoGoogle:hover i, .social-network a.icoVimeo:hover i, .social-network a.icoLinkedin:hover i {
	color:#fff;
}
a.socialIcon:hover, .socialHoverClass {
	color:#44BCDD;
}

.social-circle li a {
	display:inline-block;
	position:relative;
	margin:0 auto 0 auto;
	-moz-border-radius:50%;
	-webkit-border-radius:50%;
	border-radius:50%;
	text-align:center;
	width: 50px;
	height: 50px;
	font-size:20px;
}
.social-circle li i {
	margin:0;
	line-height:50px;
	text-align: center;
}

.social-circle li a:hover i, .triggeredHover {
	-moz-transform: rotate(360deg);
	-webkit-transform: rotate(360deg);
	-ms--transform: rotate(360deg);
	transform: rotate(360deg);
	-webkit-transition: all 0.2s;
	-moz-transition: all 0.2s;
	-o-transition: all 0.2s;
	-ms-transition: all 0.2s;
	transition: all 0.2s;
}
.social-circle i {
	color: #fff;
	-webkit-transition: all 0.8s;
	-moz-transition: all 0.8s;
	-o-transition: all 0.8s;
	-ms-transition: all 0.8s;
	transition: all 0.8s;
}

a {
 background-color: #D3D3D3;
}
ul.dots * {

  box-sizing: content-box;
  list-style-type: none;
}
ul.dots a {
  text-decoration: none;
  font-size: 20px;
  color: #34495e;
}
ul.dots a:hover {
  text-decoration: none;
  font-size: 20px;
  color: #bdc3c7;
}
ul.dots li {
  display: box;
  position: relative;
  width: 100%;
  padding: 10px 0 ;
}
ul.dots li:hover {
  background: #2c3e50;
}
ul.dots li span {
  display: block;
  -webkit-border-radius: 30px;
  -moz-border-radius: 30px;
  border-radius: 30px;
  background-color: #FFF;
  -webkit-box-shadow: 1px 1px 5px #808080;
  -moz-box-shadow: 1px 1px 5px #808080;
  box-shadow: 1px 1px 5px #808080;
  padding: 10px;
  width: 30px;
  height: 30px;
  margin: 0 auto;
  line-height: 30px;
  text-align: center;
  position: relative;
}
ul.dots li mark {
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
  border: 2px solid #FFF;
  width: 20px;
  height: 20px;
  background-color: #FF6B6B;
  position: absolute;
  top: -5px;
  left: -10px;
  font-size: 10px;
  line-height: 20px;
  font-family: 'Roboto', sans-serif;
  font-weight: 400;
  color: #FFF;
  font-weight: 700;
}
ul.dots li mark.big {
  width: 30px;
  height: 30px;
  -webkit-border-radius: 30px;
  -moz-border-radius: 30px;
  border-radius: 30px;
  line-height: 30px;
  font-size: 16px;
  top: -10px;
  left: -15px;
}
ul.dots li mark.green {
  background-color: #27ae60;
}
ul.dots li mark.blue {
  background-color: #3498db;
}
ul.dots > li > a > span > mark {
  -webkit-animation-name: bounceIn;
          animation-name: bounceIn;
  -webkit-transform-origin: center bottom;
      -ms-transform-origin: center bottom;
          transform-origin: center bottom;
  -webkit-animation-duration: 1s;
          animation-duration: 1s;
  -webkit-animation-fill-mode: both;
          animation-fill-mode: both;
-webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;
}
ul.dots > li:hover > a > span > mark {
  -webkit-animation-name: bounce;
          animation-name: bounce;
}
ul.dots > li:hover > a > span > mark.rubberBand {
  -webkit-animation-name: rubberBand;
          animation-name: rubberBand;
}

ul.dots > li:hover > a > span > mark.swing {
  -webkit-transform-origin: top center;
      -ms-transform-origin: top center;
          transform-origin: top center;
  -webkit-animation-name: swing;
          animation-name: swing;
}
ul.dots > li:hover > a > span > mark.tada {
  -webkit-animation-name: tada;
          animation-name: tada;
}
ul.dots > li:hover > a > span > mark.wobble {
  -webkit-animation-name: wobble;
          animation-name: wobble;
}
li {
  list-style-type: circle;
}

code {
  background: #ecf0f1;
} */

</style>
