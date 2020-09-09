Functions And Animation
=======================
In this assignment you will write a program using [P5](https://editor.p5js.org/) that makes shapes change over time to create an animation. You may find slides 146 - 181 in the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) helpful.  

P5's `draw()` function is repeatedly run 60 times a second. Try running the following simple animation program to see how it works:
```javascript
var diam = 40;

function setup() {
  createCanvas(400, 400);
  noFill();
}

function draw() {
  circle(200, 200, diam);
  diam = diam + 5;
}
```
We can slow down `draw()` with `frameRate()`. A frame rate of 20 is only one third as fast as the default rate of 60. Now try running this version of the program to see how it works:
```javascript
var diam = 40;
function setup() {
  createCanvas(400, 400);
  noFill();
  frameRate(20);
}

function draw() {
  circle(200, 200, diam);
  diam = diam + 5;
}
```

For this assignment you will write your own program that uses the repeating `draw()` function to create an animation. The animation is created by drawing the same shape or shapes over and over again, with a small pause between each change. Each time the shape is drawn, some aspect will change. You may use any drawing functions that you would like, your animation does not have to look any other. Scroll down and click on the links below to see samples of other students work. Have fund and be creative!    

Program Requirements
--------------------
* Your program will need variables for each aspect of the shape that changes
* It will need at least two functions definitions: `function setup()` and `function draw()`  
* Submit the URL of your finished program by choosing *File | Share* and copying the URL in the *Present* box to Google classroom



Optional   
--------
* You might try putting a call to `smooth()` in `function setup()`
* A little opacity in combination with `smooth()` can achieve some surprising results
* You may want to include an [`if`](https://p5js.org/reference/#/p5/if-else) statement, so that if your shape gets too big or goes off the screen, you can erase the screen and set the variables back to their initial values.
* You may want to call the `frameRate()` function in `function setup()` to adjust how quickly the screen is drawn.   

Samples of Student Work   
-----------------------   
[Sally](https://editor.p5js.org/sahong3/present/EAeJh3fOg)  
[Damien](https://editor.p5js.org/dabogdon/present/dzmQig5nj)   
[Rachel](https://editor.p5js.org/raroyer/present/RhvJ97eGp)   
[Miachael](https://editor.p5js.org/mimui/present/stHN1OdDX)   
[Benjamin](https://studio.code.org/projects/gamelab/bTJqPpBTQP6eWc4D24BbpY7q4DpICyeNrl71HDooxR8)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/7Cg7LWTVt)   
[Tobias](https://editor.p5js.org/tozuercher/present/VzuH67YTT)   
[Niko](https://editor.p5js.org/NikoTsu/present/W1TZ2e-1r)   
[Benjamin](https://studio.code.org/projects/gamelab/VnnQXQrHuT8ceO4T1lkBiLzwxqJiKgtqaQjSiHw0sKU)   
[Marco](https://editor.p5js.org/malee21/present/h0Ssrwjb5)   
[Michaela](https://editor.p5js.org/michaela29/present/IY5W2TjE)   
[Katelyn](https://editor.p5js.org/jizhang6/full/60YQnrNv)   
[Curtis](https://editor.p5js.org/culee/present/QKntQP8Y)    
[Duan](https://editor.p5js.org/Duan25/present/cGVlVGgc)   
[Nikhita](https://editor.p5js.org/Bluesnow/full/pGp93tiu)   
[Doris](https://trinket.io/embed/python/f210274aac?outputOnly=true&runOption=run&start=result)   
[Briana](https://trinket.io/embed/python/73fa1789cb?outputOnly=true&runOption=run&start=result)   
[David](https://trinket.io/embed/python/22e0879ae0?outputOnly=true&runOption=run&start=result)   
[Marc](https://trinket.io/embed/python/ee4d2b35a3?outputOnly=true&runOption=run&start=result)   
[David](https://trinket.io/embed/python/f1331ece45?outputOnly=true&runOption=run&start=result)   
[Jan](https://trinket.io/embed/python/bab5598f75?outputOnly=true&runOption=run&start=result)   
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
