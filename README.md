
# Venn Diagram

Given 2 sets and their union create a 2 circle Venn diagram (maybe 3 in the future)

This is the formula I use to calculate the area when the union point is right in the middle of the smller circle (x).

StartAreaU=(AreaX*((AngleX)/(EasyPI))-(DistX*arcDist*.5))+(AreaY*((AngleY)/(EasyPI))-(DistY*arcDist*.5))

This formula is a mess.  
I am argueing with myself if I want this project to be educational or if I just want to reach the end goal.  
If it were to be educational I would have to explain how I came up with that crazy formula.  
I would also need to find a better way to show the formula.  It hurts my eyes.

Here is an easy formula. This something digestable.  
The first step to this problem is deciding how big the circles need to be.  
Well the user is going to do that.
As the programmer you need to tell the computer what the radius of the circle should be.

* Area = Pi R^2

Lets use algebra to isolate the R

* Area/Pi=R^2

* SQRT(Area/Pi)=R


When you look at the diagram now it looks like two Circle but, it is 3 shapes.
Each shape is made up of two arcs.  I want to highlight that.
I will make each shape highlight when I hover over it.  That means I need to change this SVG to 
a full blown HTML with a style hover added to it like I did the state game.
 
I plan to always have the smaller circle on the left by the way.

AAAnd someone else has done this project and here it is [Bens Venn Diagram](https://github.com/benfred/venn.js/blob/master/README.md)

Here is the [project](https://theowlseye.github.io/VennDiagram/VennDiagram.html)
