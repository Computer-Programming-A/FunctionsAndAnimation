Functions And Animation
=======================
In this assignment you will write a program with an animation. The animation is created by drawing the same shape or shapes over and over again. Each time the shape is drawn, some aspect will change. You may use any drawing function that you would like, your animation does not have to look any other. Scroll down and click on the links below to see samples of other students work. Have fund and be creative! You may find the following example of a simple animation program helpful:
<pre><code>
from processing import *

diam = 40

def setup():
  size(300,300)
  noFill()

def draw():
  global diam
  ellipse(150, 150, diam, diam)
  diam = diam + 5
run()
</code></pre>   
Program Requirements
--------------------
* Your program will need variables for each aspect of the shape that changes
* It will need at least two functions definitions: `def setup()` and `def draw()`.   

Optional   
--------
* You might try putting `smooth()` in `def setup()`
* A little opacity in combination with `smooth()` can achieve some surprising results
* You may want to include an `if` statement, so that if your shape gets too big, you can erase the screen and set the variables back to their initial values.
* You may want to call the `frameRate()` function in def setup() to adjust how quickly the screen is drawn.   

Samples of Student Work   
-----------------------   
[Nghi](https://trinket.io/embed/python/88d0ffaaf1?outputOnly=true&runOption=run&start=result)   
[Raineh](https://trinket.io/embed/python/a78be9a0f8?outputOnly=true&runOption=run&start=result)   
[Kelly](https://trinket.io/embed/python/f936c54028?outputOnly=true&runOption=run&start=result)   
[Kevin](https://trinket.io/embed/python/a0cf399979?outputOnly=true&runOption=run&start=result)  
[Samantha](https://trinket.io/embed/python/c251004479?outputOnly=true&runOption=run&start=result)   
[Alyssa](https://trinket.io/embed/python/eb659f08e4?outputOnly=true&runOption=run&start=result)   
[Emma](https://trinket.io/embed/python/d8eec037c2?outputOnly=true&runOption=run&start=result)   
[Annie](https://trinket.io/embed/python/3f4e2288bd?outputOnly=true&runOption=run&start=result)   
