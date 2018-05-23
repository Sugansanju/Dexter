<template>
  <div class="home">
    <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
      <a class="navbar-brand" href="#">
         <img src="../assets/dexter.png" width="50" height="50" alt="Dexter">Dexter Dojo</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
        </ul>
        <form class="form-inline">
         <div class="inset">
           <img src="../assets/profile.png">
         </div>
         <div class="dropdown px-3">
     <button class="btn clr dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
  suganya
     </button>
     <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
       <a class="dropdown-item" href="#">Setting</a>
       <a class="dropdown-item" href="#">Logout</a>
     </div>
   </div>
    </form>
      </div>
    </nav>
    <div class="container">
      <div class="row"style="margin-top:100px;">
        <div class="col-sm-4" >
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
<div class="col-md-6" >
<div class="card card1 hvr-grow-shadow float-left px-2 text-center">
  <div class="card-body text-center">
    <button class="btn btn-5"><i class="fa fa-plus"></i></button>
    </a>
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
.clr{
  background-color: #f8f9fa;
}
.inset img {
    -webkit-background-size: 32px 32px;
    background-size: 32px 32px;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    display: block;
    margin: -1px;
    overflow: hidden;
    position: relative;
    height: 32px;
    width: 32px;
    z-index: 0;
}
.btn-4{
        border-radius:20px;
        box-shadow: 2px 2px;
        font-size: 18px;
        color: #000;
        margin: auto;
}
.btn-5 {
    background-color: DodgerBlue;
    border-radius:50px;
    color: white;
    margin-top:29px;
    padding: 12px 16px;
    font-size: 16px;
    cursor: pointer;
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
</style>
