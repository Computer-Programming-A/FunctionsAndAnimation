Functions And Animation
=======================
In this assignment you will write a program with an animation. The animation is created by drawing the same shape or shapes over and over again. Each time the shape is drawn, some aspect will change. You may use any drawing functions that you would like, your animation does not have to look any other. Scroll down and click on the links below to see samples of other students work. Have fund and be creative! You may find the following example of a simple animation program helpful:
```python
diam = 40

def setup():
  size(300,300)
  noFill()

def draw():
  global diam
  ellipse(150, 150, diam, diam)
  diam = diam + 5
```
Program Requirements
--------------------
* Your program will need variables for each aspect of the shape that changes
* It will need at least two functions definitions: `def setup()` and `def draw()`  

Putting your program on Trinket
--------------------
Trinket allows you to write, run and share Python programs online. 
* Go to [trinket.io](https://trinket.io/) and sign up
* Choose *New Trinket | Python* (Not Python3)
* Add `from processing import *` at the top of your program
* Add `run()` at the bottom
* *Save* your trinket program
* To submit the URL of your finished program to Google classroom, choose *Share | Link*

Optional   
--------
* You might try putting a call to `smooth()` in `def setup()`
* A little opacity in combination with `smooth()` can achieve some surprising results
* You may want to include an `if` statement, so that if your shape gets too big or goes off the screen, you can erase the screen and set the variables back to their initial values.
* You may want to call the `frameRate()` function in `def setup()` to adjust how quickly the screen is drawn.   

Samples of Student Work   
-----------------------   
[Andrew](https://trinket.io/embed/python/b74d7af066?outputOnly=true&runOption=run&start=result)   
[Nghi](https://trinket.io/embed/python/88d0ffaaf1?outputOnly=true&runOption=run&start=result)   
[Raineh](https://trinket.io/embed/python/a78be9a0f8?outputOnly=true&runOption=run&start=result)   
[Kelly](https://trinket.io/embed/python/f936c54028?outputOnly=true&runOption=run&start=result)   
[Kevin](https://trinket.io/embed/python/a0cf399979?outputOnly=true&runOption=run&start=result)  
[Samantha](https://trinket.io/embed/python/c251004479?outputOnly=true&runOption=run&start=result)   
[Alyssa](https://trinket.io/embed/python/eb659f08e4?outputOnly=true&runOption=run&start=result)   
[Emma](https://trinket.io/embed/python/d8eec037c2?outputOnly=true&runOption=run&start=result)   
[Annie](https://trinket.io/embed/python/3f4e2288bd?outputOnly=true&runOption=run&start=result)   
[Andrew](https://trinket.io/embed/python/c7c0bdc791?outputOnly=true&runOption=run&start=result)   
[Henry](https://trinket.io/embed/python/f9fbbaceb1?outputOnly=true&runOption=run&start=result)   
[Jeffrey](https://trinket.io/embed/python/e99aec795c?outputOnly=true&runOption=run&start=result)   
[Wesley](https://trinket.io/embed/python/b1472548b2?outputOnly=true&runOption=run&start=result)   
[Kelsy](https://trinket.io/embed/python/cc17da4474?outputOnly=true&runOption=run&start=result)   
[Jacob](https://trinket.io/embed/python/4675fbddeb?outputOnly=true&runOption=run&start=result)   
[Brian](https://trinket.io/embed/python/e71de91ca7?outputOnly=true&runOption=run&start=result)   
[Winnie](https://trinket.io/embed/python/9d170cb4b1?outputOnly=true&runOption=run&start=result)   
[Connie](https://trinket.io/embed/python/218f78c824?outputOnly=true&runOption=run&start=result)   
[Ryan](https://trinket.io/embed/python/0c57022ca5?outputOnly=true&runOption=run&start=result)   
[Brenton](https://trinket.io/embed/python/d7c00c274b?outputOnly=true&runOption=run&start=result)   
[Xiao Qin](https://trinket.io/embed/python/3343236f33?outputOnly=true&runOption=run&start=result)   
