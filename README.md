#Starburst

A collection of animated PNG sequences for use as loading indicators in your Apple Watch app.

###Types


**Disperse:**

![](gifs/disperse.gif)

Recommended duration: 6s
<br>
<br>


**Bang:**

![](gifs/bang.gif)

Recommended duration: 5s
<br>
<br>


**Ripple:**

![](gifs/ripple.gif)

Recommended duration: 6s
<br>
<br>


**Wave:**

![](gifs/wave.gif)

Recommended duration: 8s
<br>
<br>

**Nebula:**

![](gifs/nebula.gif)

Recommended duration: 10s
<br>
<br>

##Instructions
To create image based animations for your Apple Watch app, first drag your desired image sequence folder into your WatchKit App's Images.xcassets. Then create a `WKInterface` image object in your storyboard and set the image name to the image sequence name without any numbers.

For example, if you want to use the disperse animation, set your image file to: "disperse_.".

Then set its respective duration, as recommended above.

