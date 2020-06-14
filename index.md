<html>
	<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/w3css/3/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
<body>
<section>
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
</section>

<h1>CONTENT CREATOR</h1>

<p>Recommended by 4 out of 5 people who recommend things. From trying new games to climbing mountains, the AxtonG channels work towards following a dream, no matter what that dream might be at the time.</p>


<footer class="w3-container w3-padding-64 w3-center w3-black w3-xlarge">
	<h3 class="w3-wide">Links</h3>
  <a href="https://www.twitch.tv/axtong"><i class="fa fa-twitch"></i></a>
  <a href="https://youtube.com/axtong"><i class="fa fa-youtube"></i></a>
  <a href="https://twitter.com/AxtonGTV"><i class="fa fa-twitter"></i></a>
  <a href="https://discord.com/invite/HmBAzC4"><i class="fa fa-microphone"></i></a>
  <a href="https://patreon.com/AxC"><i class="fa fa-money"></i></a> 
  <a href="https://streamlabs.com/axtong/tip"><i class="fa fa-dollar"></i></a>
  <a href="https://www.instagram.com/axtonog/"><i class="fa fa-instagram"></i></a> 
  <a href="mailto:contactaxton@gmail.com"><i class="fa fa-inbox"></i></a>
</footer>

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
</body>
</html>
