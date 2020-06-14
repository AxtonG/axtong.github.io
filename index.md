<html>
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


<section>
	<h3 class="w3-wide">Links</h3>
	<a href="https://www.twitch.tv/axtong">Twitch</a><br>
  <a href="https://youtube.com/axtong">YouTube</a><br>
  <a href="https://twitter.com/AxtonGTV">Twitter</a><br>
  <a href="https://discord.com/invite/HmBAzC4">Discord</a><br>
  <a href="https://patreon.com/AxC">Patreon</a><br>
  <a href="https://streamlabs.com/axtong/tip">Donations</a><br>
  <a href="https://www.instagram.com/axtonog/">Instagram</a><br>
  <a href="mailto:contactaxton@gmail.com">Email</a><br>
</section>


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
