# Background-Color-Thief
This script is to detect background color of an image. Thanks for Color-Theif (https://github.com/lokesh/color-thief/) for such a great work. 
Here I have used some code from Color-Theif.

##How To Use

####HTML markup
```js
<img src="source.jpg" id="backgroundImage"/>
<div id="backGroundColor"></div>
```

####Javascript
```js
var backgroundColorThief = new BackgroundColorTheif();
var rgb = backgroundColorThief.getBackGroundColor(document.getElementById("backgroundImage"));
document.getElementById("backGroundColor").style.backgroundColor = 'rgb(' + rgb[0] + ',' + rgb[1] + ',' + rgb[2] +')';
```
##Demo

[Click here] (http://demo.sodhanalibrary.com/get-background-color.html) to seee demo 

##Algoirithm behind this script

Most dominant color of edges and corners of image can be background color of the image. [Click here] () for more explanation
