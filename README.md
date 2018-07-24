# pbaf
<!--school website-->
<!DOCTYPE html>
 <html lang="en">
  <head>
   <title>Pbaf</title>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="pssbaf.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
      html { 
  background: url("cartooncloud.jpg") no-repeat center center fixed; 
  background-size: cover;
}

body{
	 height: 100%;
	 width: 100%;
     margin: 0;
	 background-color:000000;
     font-family:Comic Sans MS;
	 font-size:auto;
	 
}


/*Header Wrap*/
 .preheader{
	width:100%;
	height:300px;
	padding:0px;
	padding-top: 10px;
	background-color:#1F1F1F;
	text-align:center;
 }
 
.preheader h1{
	font-family:forte;
	color:teal;
}
/*Logo*/
.preheader img{
	display: block;
    float: left;
    height: auto;
    overflow: hidden;
    padding: 0;
    text-indent: -9999px;
    width: 350px;
	transition: 0.7s;
}

.preheader a:hover{
	cursor:pointer;
}


/*Sticky+responsive header*/
.header{
  font-family:georgia;
  padding: 0px;
   padding-top: 10px;
   padding-bottom: 20px;
   text-align:center;
   overflow:hidden;
  background-color: #1AD3A3;
  color: white;
  height:50px;
  width:100%;
}
.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}
.header a:hover{
  background-color: #ddd;
}


@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
}

.dropdown {
    float: left;
    overflow: hidden;
}

.dropdown .dropbtn {
    font-size: 18px;    
    border: none;
    outline: none;
    color: black;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
    transition: 0.4s;
}

.header a:hover, .dropdown:hover .dropbtn {
    background-color: #ddd;
	cursor:pointer;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: black;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    float: none;
    color: #ffcc;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {
    background-color: dodgerblue;
    color:black;
	border-radius: 0;
}

.dropdown:hover .dropdown-content {
    display: block;
}


/*page body and information*/
.info{
    padding: 16px;
}
.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}

.sticky + .info {
  padding-top: 102px;
}

a {
	text-decoration: none;
}

.linkx {
	background-color:#1F1F1F;
	transition:0.4s;
    border: none;
	width: 500px;
    color: white;
    padding: 20px;
    text-align: center;
    text-decoration: bold;
	font-family:georgia;
    display: block;
    font-size: 30px;
    margin: 4px 2px;
}
.linkx:hover{
	box-shadow: 5px 10px 18px black;
	background-image:url('blue.jpg');
	background-size:cover;
	cursor:pointer;
	color:greenyellow;
	opacity:0.8;
	
}

i{
	padding: 3px;
	color:white;
}



/*footer*/
#wrap {
  min-height: 100%;
}

#main {
  overflow: auto;
  padding-bottom: 180px;
  /* must be same height as the footer */
}

#footer {
  position: relative;
  margin-top: -180px;
  /* negative value of footer height */
  height: 500px;
  width:100%;
  clear: both;
  background-color: black;
  opacity:0.9;
  color:silver;
  text-align:center;
  padding-top: 10px;
  padding:0px;
}

/*foot*/
.foot{
	background-color:#1F1F1F;
	color:white;
	font-family:courier;
	font-style:underline;
	width:100%;
	padding:0;
	height:50px;
	text-align:center;
	padding-top:10px;
}




    </style>
 
 </head>
  
  <body> 
  
<div class="preheader">
        <a href="home.html"><img src="pssbafutlogo.png"></img></a>
</div>

          <div class="header" id="myHeader">
		  <div class="dropdown">
		<button class="dropbtn">Home</button> 
		</div>
  <div class="dropdown">
    <button class="dropbtn">About Us</button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
    </div>
  </div> 
  <div class="dropdown">
  <button class="dropbtn">Academics
    </button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
    </div>
  </div>
  <div class="dropdown">
  <button class="dropbtn">Campus Life
    </button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
      <a href="#">Link 4</a>
      <a href="#">Link 5</a>
    </div>
  </div>
  <div class="dropdown">
  <button class="dropbtn">Admission
    </button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
      <a href="#">Link 4</a>
    </div>
  </div>
  <div class="dropdown">
  <button class="dropbtn">Contact/Support
    </button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
      <a href="#">Link 4</a>
    </div>
  </div>
</div>


<div class="info"><!--the body of the page goes in here-->
</br>
</br>
</br>
</br>
</br>
</br>
<a href="home.html"><button class="linkx"><i class="fa fa-home" aria-hidden="true"  style="font-size:40px;" ></i>HOME</button></a></br>
<a href="#"><button class="linkx"><i class="fa fa-clock-o" aria-hidden="true"  style="font-size:40px;"></i>ABOUT US</button></a></br>
<a href="#"><button class="linkx"><i class="fa fa-mortar-board" aria-hidden="true"  style="font-size:40px;"></i>ACADEMICS</button></a></br>
<a href="#"><button class="linkx"><i class="fa fa-group" aria-hidden="true" style="font-size:40px;"></i>CAMPUS LIFE</button></a></br>
<a href="#"><button class="linkx"><i class="fa fa-pencil-square" aria-hidden="true" style="font-size:40px;"></i>ADMISSION</button></a></br>
<a href="#"><button class="linkx"><i class="fa fa-phone-square" aria-hidden="true" style="font-size:40px;"></i>CONTACT /SUPPORT</button></a></br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
<!--Place a div here-->

</br>
</br>
</br>
</div>

  <div id="wrap">
  <div id="main"></div>
</div>
   
   <div id="footer">
            <h4>footer</h4>
   </div>
   
   <div class="foot">copyright</div>
   
   <script>
  window.onscroll = function() {myFunction()};

var header = document.getElementById("myHeader");
var sticky = header.offsetTop;

function myFunction() {
  if (window.pageYOffset > sticky) {
    header.classList.add("sticky");
  } else {
    header.classList.remove("sticky");
  }
}



</script>
   
 
   
   </body>
   </html>
   
   
