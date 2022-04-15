<!DOCTYPE html>
<html lang="en">
<head>
<title>For you!</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
.w3-third img{margin-bottom: -6px; opacity: 0.8; cursor: pointer}
.w3-third img:hover{opacity: 1}
</style>
</head>
<body class="w3-light-grey w3-content" style="max-width:1600px">


<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-white w3-animate-left w3-text-grey w3-collapse w3-top w3-center" style="z-index:3;width:300px;font-weight:bold" id="mySidebar"><br>
  <h3 class="w3-padding-64 w3-center"><b>For<br>Kait!</b></h3>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-hide-large">CLOSE</a>
  <a href="#" onclick="w3_close()" class="w3-bar-item w3-button">My favorite Pictures!</a> 
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">Something for you!</a>
  
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-white w3-xlarge w3-padding-16">
  <span class="w3-left w3-padding">First Month!</span>
  <a href="javascript:void(0)" class="w3-right w3-button w3-white" onclick="w3_open()">☰</a>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">

  <!-- Push down content on small screens --> 
  <div class="w3-hide-large" style="margin-top:83px"></div>
  
  <!-- Photo grid -->
  <div class="w3-row">
    <div class="w3-third">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_7506.JPEG?raw=true" style="width:100%" onclick="onClick(this)" alt="The first time we decided to hangout! -January 31,2022">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_8761.JPEG?raw=true" style="width: 345px; height: 410px;" onclick="onClick(this)" alt="Skyblossom Galentines day!! -February 13,2022">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_2429.jpeg?raw=true" style="width: 345px; height:405px;" onclick="onClick(this)" alt="The day we visited my grandma and went to go get sushi! -March 7,2022">
    </div>

    <div class="w3-third">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_3663.JPG?raw=true" style="width:100%" onclick="onClick(this)" alt="2nd time at ddonggo!! - February 11,2022">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/D73704B8-0C3A-433A-BD0F-39F4EC3A4E2D.jpeg?raw=true" style="width:100%" onclick="onClick(this)" alt="The day we went to Deep Ellum! -March 20,2022">
      <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_2996.jpeg?raw=true" style="width:100%" onclick="onClick(this)" alt="Armnhmr! Our first concert/Rave together! -March 2,2022">
    </div>
    
    <div class="w3-third">
        <img src="https://github.com/maka0302/For-Kait-/blob/main/omg.jpg?raw=true" style="width: 350px; height: 350px;" onclick="onClick(this)" alt="Our first time together in ddonggo! -February 6,2022">
        <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_2360.jpeg?raw=true" style="width:100%" onclick="onClick(this)" alt="We visited my grandma! hehe -March 7,2022">
        <img src="https://github.com/maka0302/For-Kait-/blob/main/LP2.JPEG?raw=true" style="width:100%" onclick="onClick(this)" alt="The facetime call where I folded hard :D -February 7,2022">
        <img src="https://github.com/maka0302/For-Kait-/blob/main/Photo%20on%202-11-22%20at%208.23%20PM.jpg?raw=true" style="width:100%" onclick="onClick(this)" alt="First time in Mozart! -February 11,2022">
      </div>
  </div>

  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- About section -->
  <div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id="about">
    <h4><b>For you!</b></h4>
    <img src="https://github.com/maka0302/For-Kait-/blob/main/IMG_7514.JPEG?raw=true" alt="For you!" class="w3-image w3-padding-32" width="600" height="650">
    <div class="w3-content w3-justify" style="max-width:600px">
      <h4>Dear Kaitlyn</h4>
      <p>Let me start with I'm glad that I met you! Ever since I met you life has been so bright and the future seems so much more brighter now! I know that this is our honeymoon phase but let me express how much I cherish what we have going and how much I'm so thankful for everything! Thankful for your care,worries,love, all the laughs that we have,our little adventures and etc you name it!! I know that this is a bit wonky and like a bit bad  but I hope that this would put a smile in your face and hopefully make your day!<br> I also would like to include my 
      </p>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-grey">  
    <div class="w3-row-padding">
      <div class="w3-third">
        <h3>Note:</h3>
        <p>Your personal folder tries to make you a website ;-; I hope this makes you smile and make your day!! :D</p>      
      </div>
    
      <div class="w3-third">
        <h3>Things I want to say to you</h3>
        <p>
          <span class="w3-tag w3-dark-grey w3-margin-bottom">I</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Want</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">To</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Say</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">That</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">I</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Love</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">You</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">So</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Much</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Thankful</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">For</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">You</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Kaitlyn!</span>
        </p>
      </div>
    </div>
  </footer>
  
  <div class="w3-black w3-center w3-padding-24"><a href="https://open.spotify.com/playlist/0iMahFLobc6KnckJm1FcFc?si=010bd03ee67e4785&nd=1" title="Spotify" target="_blank" class="w3-hover-opacity">Click the link!</a></div>

  <div class="w3-black w3-center w3-padding-24"><a href="https://www.notion.so/Mark-Kait-s-Schedule-b8b8a228337440ee89b7bbbd5e61c1b8" title="Notion" target="_blank" class="w3-hover-opacity">Our Notion!</a></div>
<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

</script>


</body>
</html>
