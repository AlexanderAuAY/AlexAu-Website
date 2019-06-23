## Welcome to my website!

<html>
        <h3>Contents</h3>
        <ul>
           <li> <a href="#one">Khan Academy - Fish Tank</a></li>
        <li><a href="#two">Second Post</a></li>
        </ul>
        
        <h2 id="one">Fish Tank</h2>
        <h6>Made in Khan Academy within the guidance of their modules</h6>
        
```var centerX = 200;
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
        
        <p>Hewwo, I am wwiting a post wegawding copied pastas. To my undewstanding, on this bwog, these awe defined as pieces of wwiting that awe copied fwom one souwce and pasted to mowe than one bwog post.</p>

I wouwd wike to cwawify that evewything w wwite is owiginaw. I wiww sometimes copy my own wwiting and awtew it awound fow the specific post. Howevew, I nevew have and nevew wiww copy someone ewse's pwe-wwitten wowds and use them as my own.

I'm not a theef. Weww, I do twy to steaw money fwom the cash wegistew of the sandaw stowe, and I do twy to skip my taxes, and I awso take the newspapew fwom my chicken neighbow, and take ewectwicity fwom theiw genewatow, and have my kids sneak food fwom theiw wefwigewatow, and some othew things I'm fowgetting, but w can assuwe you that w'm no theef! w'm a good, honest, hawdwowking Amewican man</p>
        
</html>
