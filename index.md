<html>

  <style>
.center {
  margin: auto;
  width: 100%;
  
  padding: 10px;
}
</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<div class="w3-container center">
<div class="w3-bar w3-black">
  <a href="https://www.twitch.tv/axtong" class="w3-bar-item w3-hover-purple">Twitch</a>
  <a href="https://youtube.com/axtong" class="w3-bar-item w3-hover-red ">YouTube</a>
  <a href="https://twitter.com/AxtonGTV" class="w3-bar-item w3-hover-blue">Twitter</a>
  <a href="https://discord.com/invite/HmBAzC4" class="w3-bar-item w3-hover-indigo">Discord</a>
  <a href="https://patreon.com/AxC" class="w3-bar-item w3-hover-orange">Patreon</a>
  <a href="https://streamlabs.com/axtong/tip" class="w3-bar-item w3-hover-teal">Donations</a>
  <a href="https://www.instagram.com/axtonog/" class="w3-bar-item w3-hover-yellow">Instagram</a>
  <a href="mailto:contactaxton@gmail.com" class="w3-bar-item w3-hover-white">Email</a>
  </div>
<div class="w3-container">
  <img class="mySlides" src="https://i.imgur.com/dKnf6jW.png"
  style="width:auto">
  <img class="mySlides" src="https://i.imgur.com/unKUrUN.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/sBIe5RV.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/dKnf6jW.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/qX8ZoIG.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/PhssuFB.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/Xgabcso.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/CtLtJku.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/H3Nu2jE.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/S2EaCZM.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/ur67QXt.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/9sJXkgT.png"
  style="width:100% height:20%">
  <img class="mySlides" src="https://i.imgur.com/vNKnzOR.png"
  style="width:100% height:20%">
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

