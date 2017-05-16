Functions And Animation
=======================
In this assignment you will write a program with an animation. The animation is created by drawing the same shape or shapes over and over again. Each time the shape is drawn, some aspect will change. You may use any drawing function that you would like, your animation does not have to look like the one above. You may find the following example of a simple animation program helpful:
 <pre><code>
   `diam = 40
    def setup():
        size(300,300)
       noFill()
     
   def draw():
       global diam
       ellipse(150, 150, diam, diam)
       diam = diam + 5</code></pre>   
Program Requirements:   
* Your program will need variables for each aspect of the shape that changes
* It will need at least two functions definitions: `def setup()` and `def draw()`.   
Optional   
* You might try putting `smooth()` in `def setup()`
* A little opacity in combination with `smooth()` can achieve some surprising results
* You may want to include an `if` statement, so that if your shape gets too big, you can erase the screen and set the variables back to their initial values.
* You may want to call the `frameRate()` function in def setup() to adjust how quickly the screen is drawn.   

Samples of Student Work   
-----------------------   
