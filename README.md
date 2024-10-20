<meta chartes="utf-8" />
<html>
 <head>
 <title>W3.CSS</title>
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 
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
<div class="w3-sidebar w3-bar-block w3-black w3-card" style="width:130px">
  <h5 class="w3-bar-item"></h5>
  <button class="w3-bar-item w3-button tablink" onclick="openLink(event, '1')">Qui est-il?</button>
  <button class="w3-bar-item w3-button tablink" onclick="openLink(event, '2')">Biographie</button>
  <button class="w3-bar-item w3-button tablink" onclick="openLink(event, '3')">Oeuvres</button>
   <button class="w3-bar-item w3-button tablink" onclick="openLink(event, '4')">À retenir</button>
</div>

<div style="margin-left:130px">
  <div class="w3-padding"> <p id="para5" style="border: 1px solid black; padding: 10px;"><b>ARISTOTE </b></p></div>

  <div id="1" class="w3-container city w3-animate-opacity" style="display:none">
  <br><p> Aristote est un philsophe grec. </p><br>
  <div style="display:flex"> 
    <img src="image/a1.jpg"> 
    <img src="image/a2.jpg"> 
 </div> 
  
  </div>

  <div id="2" class="w3-container city w3-animate-left" style="display:none">
    <h2>Slide in from left</h2>
    <p>Paris is the capital of France.</p> 
    <p>The Paris area is one of the largest population centers in Europe, with more than 12 million inhabitants.</p>
  </div>

  <div id="3" class="w3-container city w3-animate-top" style="display:none">
    <h2>Slide in from top</h2>
    <p>Tokyo is the capital of Japan.</p>
    <p>It is the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
  </div>

  <div id="4" class="w3-container city w3-animate-right" style="display:none">
    <h2>Slide in from right</h2>
    <p>London is the capital city of England.</p>
    <p>It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  </div>

  

 </div>













 <script>
 function openLink(evt, animName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("city");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(animName).style.display = "block";
  evt.currentTarget.className += " w3-red";
 }
 </script>
 
 
 
 
  
 
 
  </body>
 
