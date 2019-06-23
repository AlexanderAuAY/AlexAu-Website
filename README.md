## Welcome to my website!

<html>
        <h3>Contents</h3>
        <ul>
        <li> <a href="#one">Khan Academy - Fish Tank</a></li>
        <li><a href="#two">Khan Academy - JQuery Quiz</a></li>
        <li> <a href="#three">Khan Academy - Mad Libs</a></li>
        <li><a href="#four">Khan Academy - Paint Splatter</a></li>
        <li> <a href="#five">Khan Academy - Word Game</a></li>
        <li><a href="#six">Khan Academy - Asteroids Spaceship</a></li>
        <li> <a href="#seven">Grade 11 - Twenty One Game</a></li>
        <li><a href="#eight">Grade 11 - String Manipulation</a></li>
        <li> <a href="#nine">Grade 11 - Summative</a></li>
        <li><a href="#ten">Coding Challenge - Fire</a></li>
        <h2 id="one">Fish Tank</h2>
        <h6>Made in Khan Academy within the guidance of their modules</h6>
        
```var centerX = 200;\
var centerY = 100;
var bodyLength = 118;
var bodyHeight = 74;
var bodyColor = color(162, 0, 255);


var drawFish = function(centerX,centerY,bodyHeight,bodyColor)
{
noStroke();
fill(bodyColor);
// body
ellipse(centerX, centerY, bodyLength, bodyHeight);
// tail
var tailWidth = bodyLength/4;
var tailHeight = bodyHeight/2;
triangle(centerX-bodyLength/2, centerY,
         centerX-bodyLength/2-tailWidth, centerY-tailHeight,
         centerX-bodyLength/2-tailWidth, centerY+tailHeight);
// eye
fill(33, 33, 33);
ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);
} ;

drawFish (316,298,84,156);
drawFish (209,186,15,200);
drawFish (133,85,126,99);
```
          <h2 id="two">Second Post</h2>
        <h6>September 12th, 2011</h6>
        
       Hewwo, I am wwiting a post wegawding copied pastas. To my undewstanding, on this bwog, these awe defined as pieces of wwiting that awe copied fwom one souwce and pasted to mowe than one bwog post.

        
</html>
