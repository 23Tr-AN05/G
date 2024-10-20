<meta chartes="utf-8" />
<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
 
 <style>
    #para1{
        font-size:50px;
        text-align:center;
        color:red;
    }
      #p1{
        font-size:60px;
        text-align:center;
        color:black;
    }
    #para2{
        font-size:30px;
        text-align:center;
        color:red;
    }
    #para3{
        font-size:20px;
        text-align:left;
        color:#000000;
    }
    #para4{
        font-size:20px;
        text-align:left;
        color:#00FF00;
    }
    #para5{
        font-size:40px;
        text-align:center;
        color:#FF1000;
    }
    #p5{
        font-size:40px;
        color:#FF1000;
    }
    #para6{
        font-size:20px;
        text-align:left;
        color:#13A640;
    }
     #para7{
        font-size:30px;
        text-align:center;
        color:#C100AA;
    }
    #para8{
        font-size:30px;
        text-align:left;
        color:#FF0000;
    }
    #para9{
        font-size:20px;
        text-align:right;
        color:#000000;
    }
     #para10{
        font-size:20px;
        text-align:right;
        color:#FF0000;
        background-color:yellow;
    }
    mark{
        background-color:yellow;
        color:black;
    }
    #m1{
        background-color:#FFDCDA;
        color: black;
    }
    #m2{
        background-color:#8FFF6D;
        color: black;
    }
    #m3{
         background-color:#C1FFFC;
        color: black;
    }
    #m4{
        background-color:#00FFFF;
        color:black;
    }
    #p1{
        text-align:center;
    }
    #p2{
        font-size:20px;
        text-align:center;
    }
   
 </style></head>

 <body>
 <h1 id="para1">CULTURE GÉNÉRALE </h1>
 <br> <br>

<div class="w3-container">
  <div class="w3-padding"> <p id="para5" style="border: 1px solid black; padding: 10px;"><b>ARISTOTE </b></p></div>

  <div class="w3-bar w3-black">
    <button class="w3-bar-item w3-button tablink w3-red" onclick="openCity(event,'1')">Qui est-il</button>
    <button class="w3-bar-item w3-button tablink" onclick="openCity(event,'2')">Biographie</button>
    <button class="w3-bar-item w3-button tablink" onclick="openCity(event,'3')">Oeuvres</button>
    <button class="w3-bar-item w3-button tablink" onclick="openCity(event,'4')">À retenir</button>
  </div>
  
  <div id="1" class="w3-container w3-border city">
   <br><p> Aristote est un philsophe grec. </p><br>
  <div style="display:flex"> 
    <img src="image/a1.jpg"> 
    <img src="image/a2.jpg"> 
 </div> 
  </div>

  <div id="2" class="w3-container w3-border city" style="display:none">
   <img src="image/a1.jpg" style="float:left;" /><img src="image/a2.jpg" style="float:left;" />
<div style="clear:both;"></div>
  </div>

  <div id="3" class="w3-container w3-border city" style="display:none">
    <h2>Tokyo</h2>
    <p>Tokyo is the capital of Japan.</p>
  </div>
  
  <div id="4" class="w3-container w3-border city" style="display:none">
    <h2>Tokyo</h2>
    <p>Tokyo is the capital of Japan.</p>
  </div>
</div>
<br><hr/>






 
 <script>
 function openCity(evt, cityName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("city");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " w3-red";
 }
 </script>

 
  
 
 
  </body>
 
