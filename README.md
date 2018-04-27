# processing-graphics-7-animated-square

**[Assignment Standard Operating Procedures](https://mariopineda.github.io/assignment-sops/)**

## Up to 60% - Basic Functionality
* Set your canvas to 700px x 700px
* Draw a small square on the screen (about 20 x20).
* Write code so that it will move using all 4 arrow keys (use https://processing.org/reference/keyPressed_.html and https://processing.org/reference/keyCode.html, although you could also use https://processing.org/reference/keyPressed.html, do not use this method in this assignment)

## Up to 70% - Add wrap around
Write code so that the rectangle wraps the screen when it goes off the edges.  

## Up to 80% - Add a power up
Create a variable that represents the speed the rectangle moves. When you press the ‘p’ key, it should increase the rectangles speed. In other words, from that point on, each time you press an arrow key it should jump further. You only need to press ‘p’ once and you do not need to hold it down. This new speed would last forever…  unless you tackle the last step of the assignment (below).

## Up to 90% - Proximity detection
Add a red rectangle that is 40 pixels high that covers the entire top of your screen (the top 40px should be all red).  
If your square is touching the red box, in the red box the following text should occur: “Warning: Wormhole detected ahead.  Approach with caution.”

## Up to 100% - Temporary power up
Using the timer functionality in Processing (you will have to research this on your own) have the power up last 5 seconds. In other words, five seconds after you press the ‘p’ key, your speed returns to normal.
