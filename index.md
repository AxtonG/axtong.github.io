<html>
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

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AxtonG/AxtonG.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<script>
// Automatic Slideshow - change image every 3 seconds
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
