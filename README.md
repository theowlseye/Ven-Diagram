# Venn Diagram

Given 3 sets and their union create a 3 circle diagram

Unlike most programming the SVG Path tag is very fusy about white spaces. It could be that or it could be that the little preview option does not work but, when you view it as a user it does work.

=C3^2xACOS((B9^2+C3^2-C2^2)/(2xB9xC3))+C2^2xACOS((B9^2+C2^2-C3^2)/(2xB9xC2))-0.5xSQRT((-B9+C3+C2)x(B9+C3-C2)x(B9-C3+C2)x(B9+C3+C2))
the area of the union where B9 is the distance between the centers and C2 is the radius of circle A and C3 is the radius of circle B

This formula is a mess.  
I am argueing with myself if I want this project to be educational or if I just want to reach the end goal.  
If it were to be educational I would have to explain how I came up with that crazy ass formula.  
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

So now the two sliders effect the circles and nothing is going as plan.
The test is to set the sliders each at an area to which the radius of each circle is 10.
Then with the rest of the code the circles should overlap in such a way 
that the angle from the center of each circle should be 90 degrees but that is not happening.  

Here is what is happening given the two radiuses and a given arc length where the circle connects 
there are two seperate overlapping shapes that could be made.  I will build both to figure this problem out. 


Here is the [project](https://theowlseye.github.io/VennDiagram/VennDiagram.html)
