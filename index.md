<html>

  <style>
.center {
  
  width: 100%;
  margin: auto;
  padding: 0px;
}
</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>


<div class="w3-bar w3-black w3-center"  style="height:55px">
  <a href="https://www.twitch.tv/axtong" class="w3-bar-item w3-hover-purple" style:"fontsize:100%;">Twitch</a>
  <a href="https://youtube.com/axtong" class="w3-bar-item w3-hover-red" style:"fontsize:100%;">YouTube</a>
  <a href="https://twitter.com/AxtonGTV" class="w3-bar-item w3-hover-blue" style:"fontsize:100%;">Twitter</a>
  <a href="https://discord.com/invite/HmBAzC4" class="w3-bar-item w3-hover-indigo" style:"fontsize:100%;">Discord</a>
  <a href="https://patreon.com/AxC" class="w3-bar-item w3-hover-orange" style:"fontsize:100%;">Patreon</a>
  <a href="https://streamlabs.com/axtong/tip" class="w3-bar-item w3-hover-teal" style:"fontsize:100%;">Donations</a>
  <a href="https://www.instagram.com/axtonog/" class="w3-bar-item w3-hover-yellow" style:"fontsize:100%;">Instagram</a>
  <a href="mailto:contactaxton@gmail.com" class="w3-bar-item w3-hover-white" style:"fontsize:100%;">Email</a>
  </div>
 <div class="w3-container center">
  <img class="mySlides" src="https://i.imgur.com/dKnf6jW.png"
  style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/unKUrUN.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/sBIe5RV.png"
  style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/dKnf6jW.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/qX8ZoIG.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/PhssuFB.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/Xgabcso.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/CtLtJku.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/H3Nu2jE.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/S2EaCZM.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/ur67QXt.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/9sJXkgT.png"
   style="width:100%">
  <img class="mySlides" src="https://i.imgur.com/vNKnzOR.png"
   style="width:100%">
  </div>




<script>
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 4000);
}
</script>

