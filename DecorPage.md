# ELS <!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
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
    background-color: #111;
    color: red;
    font-size: 25px;
}

.price li {
    border-bottom: 1px solid #eee;
    padding: 20px;
    text-align: center;
}

.price .grey {
    background-color: rosybrown;
    font-size: 20px;
}

.button {
    background-color: #4CAF50;
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
    background-color: rgba !important;
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

</style>
</head>
<body>
    
<h3></h3>
<h2 style="text-align:center"><p class="tab blink">Welcome To ELS Decoration Center.</p> </h2>

<p style="text-align:center">You have found your decoration team to make your event perfect.</p>

<div class="columns">
  <ul class="price">
      <img src="Images/D1.png" width="150" height="148" alt="D1"/>
    <li class="grey">Large Tents</li>
    <li>width: 15m</li>
    <li>Height: 6m</li>
    <li>Durable and safe</li>
    
    <li class="grey"><a href="Quotation.php" class="button">Request quote</a></li>
  </ul>
</div>

<div class="columns">
  <ul class="price">
     <img src="Images/D2.jpg" width="150" height="148" alt="D2"/>
    <li class="grey">Medium Tents</li>
    <li>width: 12m</li>
    <li>Height: 5m</li>
    <li>Durable and safe</li>
    <li class="grey"><a href="Quotation.php" class="button">Request quote</a></li>
  </ul>
</div>

<div class="columns">
  <ul class="price">
    <img src="Images/D3.jpg" width="150" height="148" alt="D3"/>
    <li class="grey">Small Tents</li>
    <li>width: 8m</li>
    <li>Height: 5m</li>
    <li>Durable and safe</li>
   <li class="grey"><a href="Quotation.php" class="button">Request quote</a></li>
  </ul>
</div>
<li>The main frames (upright support and beam) of the large tents are made by 84x48x3/ 122x68x3/ 150x 108x 3mm/ 203x112x4.5mm hard pressed extruded aluminum.
      The sidewalls and roof covers are manufactured with 650~ 850g/m2 PVC-coated polyester textile flame retardant to DIN4102 B1, M2. The fabric is available in block-out or tranparent.</li>

<div class="icon-bar">
    <a class="active" href="index.php"><i class="fa fa-home"></i>Home</a> 
  <a href="#"><i class="fa fa-search"></i>Search</a>
  <a href="#"><i class="fa fa-globe"></i>Locate us</a>
  
</div>
<a href="https://www.facebook.com/elseventmanagement/?pnref=lhc"><img src="Images/Facebook.jpg" width="150" height="108" alt="Facebook"/></a>
</body>
</html>

 
