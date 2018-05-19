<template>
  <div class="hello">
 <nav class="navbar navbar-light fixed-top bg-light">
    <a class="navbar-brand" href="#">
        <img src="../assets/dexter.png" width="50" height="50" alt="Dexter">Dexter Dojo
    </a>
    <form class="form-inline">
   <button class="btn btn-1 btn-white" type="submit">Signup</button>
 </form>
</nav>
<div class="container" style="margin-top:150px;">
  <div class="row">
    <div class="col-md-6 text-center">
      <img src="../assets/classrom.png">
          <h1> Happier Classrooms</h1>
          <h3>The simple way to build an amazing classroom community</h3>
    </div>
    <div class="col-sm-6">
    <div class="card card-style">
            <div class="card-body text-center">
            <input class="form-control input" type="text"  placeholder="Email/phone">
            <input class="form-control input" type="password"  placeholder="Password">
              <div class="row">
            <div class="col-md-6">
            </div>
                 <div class="col-md-6 float-right">
                                <a href="#" class="btn btn-3">forgot password?</a>
                            </div>
                        </div>
                  <div class="row">
                  <div class="col-md-6">
                  </div>
                  <div class="col-md-6 float-right">
                        <a href="#" class="btn btn-2">Signup</a>
            <a href="#/home" class="btn btn-1 btn-white">login</a>
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
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body{
  background-color:	#F0EFEC;
}
.card-style{
  box-shadow: 1px 1px #888888;
 border-radius:25px;
}
.nav {
  height:70px;
  width: 100%;
  background-color:#ffffff;
  position: relative;
}
.input {
  font-size: 15px;
  margin: 15px 0;
  padding: 10px 20px;
  border:none !important;
  border-radius: 25px;
  background-color: #eee;
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
.btn-2{
  color:#68B8B6;
}
.btn-3{
      color:#B8BBBB;
}
</style>
