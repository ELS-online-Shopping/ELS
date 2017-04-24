# ELS<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
         
        
    <Style>
    body{
    
    font-family: lucinda grande, tahoma,arial,sans-serif;
     color: black;
   background-image:url(../Images/R5.jpg);
}

body p{
    font-size: 0.8;
    line-height: 1.28;
}

#wrapper{
    width: 1080px;
    background-image:url(../Images/R4.jpg);
    margin: 0 auto;
    padding: 10px;
    border: 5px solid #dedede;
}

#banner{
    
    background-image: url(../Images/IMG-20170306-WA0027.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    border: 5px solid #dedede;
    height: 200px;
    
}
#content_area{
    float: left;
    width: 750px;
    margin: 20px 0 20px 0;
    padding: 10px;
}
#top-nav { margin:0 auto; padding:0px 0 0; height:37px; float:right;}
			#top-nav ul { list-style:none; padding:0; height:37px; float:left;}
			#top-nav ul li { margin:0; padding:0 0 0 8px; float:left;}
			#top-nav ul li a { display:block; margin:0; padding:8px 20px; color:red; text-decoration:none;}
			#top-nav ul li.active a, #top-nav ul li a:hover { color:#f8dbdb;}
#sidebar{
    float: right;
    width: 250px;
    height: 400px;
    margin: 20px 0 10px 0;
    padding: 10px;
    border: 2px solid #E3E3E3;
    
}
#footer{
    clear: both;
    width: auto;
    height: 40px;
    padding: 10px;
    border: 3px solid #E3E3E3;
    text-align: center;
    color:#fff;
    text-shadow:0.1em 0.1em #333;
    background-image: url(../Images/bg.jpg);
}

 
     .navbar{
		margin-top: 20px;
	}

#nav{
    list-style: none;
}
#nav ul{
    margin: 0;
    padding:0;
    width:auto;
    display: none;
}
#nav li{
    font-size: 24px;
    float:left;
    position:relative;
    width: 180px;
    height: 50px;
}
#nav a:link, nav a:active, nav a:visited{
    display:block;
    color: #fff;
    text-decoration:none;
}
#nav a:hover{
    color: black;
}
.feature { background:black;padding:12px;}
.feature-inner { margin:auto;width:370px; }
.feature-inner h1 {color:orange;font-size:65px;}
               .blink {
	-webkit-animation: blink .75s linear infinite;
	-moz-animation: blink .75s linear infinite;
	-ms-animation: blink .75s linear infinite;
	-o-animation: blink .75s linear infinite;
	 animation: blink .75s linear infinite;
}
@-webkit-keyframes blink {
	0% { opacity: 1; }
	50% { opacity: 1; }
	50.01% { opacity: 0; }
	100% { opacity: 0; }
}
@-moz-keyframes blink {
	0% { opacity: 1; }
	50% { opacity: 1; }
	50.01% { opacity: 0; }
	100% { opacity: 0; }
}
@-ms-keyframes blink {
	0% { opacity: 1; }
	50% { opacity: 1; }
	50.01% { opacity: 0; }
	100% { opacity: 0; }
}
@-o-keyframes blink {
	0% { opacity: 1; }
	50% { opacity: 1; }
	50.01% { opacity: 0; }
	100% { opacity: 0; }
}
@keyframes blink {
	0% { opacity: 1; }
	50% { opacity: 1; }
	50.01% { opacity: 0; }
	100% { opacity: 0; }
}
* {
    box-sizing: border-box;
}

.columns {
    float: left;
    width: 33.3%;
    padding: 8px;
}

.price {
    list-style-type: none;
    border: 1px solid #eee;
    margin: 0;
    padding: 0;
    -webkit-transition: 0.3s;
    transition: 0.3s;
    
}

.price:hover {
    box-shadow: 0 8px 12px 0 rgba(0,0,0,0.2)
        
}

.price .header {
    background-color: orange;
    color: red;
    font-size: 25px;
}

.price li {
    border-bottom: 1px solid #eee;
    padding: 20px;
    text-align: center;
}

.price .grey {
    background-image:url(../Images/T1.jpg);
    font-size: 20px;
}
.row belt{
    color: orange;
    font-size: 25px;
}

.button {
    background-color:black;
    border: none;
    color: white;
    padding: 10px 25px;
    text-align: center;
    text-decoration: none;
    font-size: 18px;
}

@media only screen and (max-width: 600px) {
    .columns {
        width: 100%;
    }
}
body {margin:0}

 .icon-bar {
    width: 100%;
    background-color: black;
    overflow: auto;
}

.icon-bar a {
    float: left;
    width: 20%;
    text-align: center;
    padding: 12px 0;
    transition: all 0.3s ease;
    color: goldenrod;
    font-size: 36px;
}

.icon-bar a:hover {
    background-color: #000;
}

.active {
    background-color: rgb !important;
}
 
div.slide-left {
  width:100%;
  overflow:hidden;
}
div.slide-left p {
  animation: slide-left 10s;
}

@keyframes slide-left {
  from {
    margin-left: 100%;
    width: 300%; 
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}
 #wrapper{
    width: 1180px;
    height: 1780px;
    background-image:url(../Images/R4.jpg);
    margin: 0 auto;
    padding: 40px;
    border: 5px solid #dedede;
}
        /* W3.CSS 4.04 Apr 2017 by Jan Egil and Borge Refsnes */
html{box-sizing:border-box}*,*:before,*:after{box-sizing:inherit}
/* Extract from normalize.css by Nicolas Gallagher and Jonathan Neal git.io/normalize */
html{-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}
body{margin:0
}
#banner{
    
    background-image: url(../Images/R4.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    border: 5px solid #dedede;
    height: 209px;
    
}


			
 
</Style>

<div id="banner">
               
            <div id="page">
			<header id="header">
				<div id="header-inner">	
					<div id="logo">
                                            <h1><a href="Home.php"><img src="Images/logo.jpg" width="150" height="148" alt="logo"/> </a></h1>
					</div>
					 
					<div class="clr"></div>
				</div>
        </div> 
          
    </head>
    
    <body>
        
         
        <div id="wrapper">
            
           <div class="columns">
  <ul class="price">
      <img src="Images/W1.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
               
</div>
           
  <div class="columns">
  <ul class="price">
      <img src="Images/W2.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
                        
                        
</div>
           <div class="columns">
  <ul class="price">
      <img src="Images/W3.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
 </div>
                 <p></p>
            <div class="columns">
  <ul class="price">
      <img src="Images/W4.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div>
                     <div class="columns">
  <ul class="price">
      <img src="Images/W5.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div> 
                 <div class="columns">
  <ul class="price">
      <img src="Images/W6.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div>
                 <div class="columns">
  <ul class="price">
      <img src="Images/W7.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div> 
                 <div class="columns">
  <ul class="price">
      <img src="Images/W8.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div> 
                 <div class="columns">
  <ul class="price">
      <img src="Images/W9.jpg" width="220" height="218" alt="IMG-20170306-WA0034"/> 
    <li class="grey">Flattering on average height</li>
    <li>Price:N$ 2 500.00 (excl VAT)</li>
    <li class="grey"><a href="Quotation.php" class="button">Order</a></li>
  </ul>
    </div> 
        <footer>
            <div class="container">
            <div class="text-center">
                
                <hr>
                
            </div>
        </div>
            <div class="row belt">
    
            <span id="m-belt-orderNum" data-num="470000">1,249</span> <span>buyers</span>
            from
            <span>more than 8 regions</span>
            experience secure trading on ELS.com.na.
            
    
        </div>
        </footer>
        </div>
        
       <p>Copyright © 2017 ELS Events. All Rights Reserved</p>
                <hr>
                <!--Copyright-->
                <p>Website by <a href="Alpha.unam.na" target="_blank" style="color: #333;">Alpha</a>.</p> 
    </body>
      
</html>
