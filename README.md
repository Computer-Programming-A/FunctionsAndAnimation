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
[Ashley](https://editor.p5js.org/ashan-voltaic/present/GsaOFoh_B)   
[Irisa](https://editor.p5js.org/irchu1/present/GYNfsvIY1)   
[Michael](https://editor.p5js.org/mibennett1/present/Nml25fTqF)   
[Joanna](https://editor.p5js.org/jogaray-velazquez/present/aqVVk50nb)   
[Brian](https://editor.p5js.org/brsen/present/ufSUNNzKR)   
[Jennie](https://editor.p5js.org/jilin20/present/8cAVGZ6qX)   
[Dat](https://editor.p5js.org/tuduong1/present/v5J5r-tbL)   
[Ailsa](https://editor.p5js.org/aiyale/present/ESh3yZ0eS)   
[Joanne](https://editor.p5js.org/joguan/present/0ovEw4E0g)   
[Sean](https://editor.p5js.org/sewong3/present/jjckswk1_)   
[Joshua](https://editor.p5js.org/joshuapaza/present/o0TmTqZNw)   
[Cyrus](https://editor.p5js.org/Wowbowbow/present/EKyfqWYqn)    
[Tommy](https://editor.p5js.org/Touyen/present/JrpIFXHqI)   
[Marissa](https://editor.p5js.org/maholmes/present/29c_z0Ffu)   
[Paolo](https://editor.p5js.org/paolo415/present/MaHyIgOXa)   
[Sally](https://editor.p5js.org/sahong3/present/EAeJh3fOg)  
[Damien](https://editor.p5js.org/dabogdon/present/dzmQig5nj)   
[Michelle](https://editor.p5js.org/michelle0/present/jS6sQi2lY)   
[Rachel](https://editor.p5js.org/raroyer/present/RhvJ97eGp)   
[Michael](https://editor.p5js.org/mimui/present/stHN1OdDX)   
[Naomi](https://editor.p5js.org/nakung/present/-rOsXMOnh)   
[Benjamin](https://studio.code.org/projects/gamelab/bTJqPpBTQP6eWc4D24BbpY7q4DpICyeNrl71HDooxR8)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/7Cg7LWTVt)   
[Tobias](https://editor.p5js.org/tozuercher/present/VzuH67YTT)   
[Audrey](https://editor.p5js.org/AudreyLau8/present/1jUChOtWx)   
[Niko](https://editor.p5js.org/NikoTsu/present/W1TZ2e-1r)   
[Benjamin](https://studio.code.org/projects/gamelab/VnnQXQrHuT8ceO4T1lkBiLzwxqJiKgtqaQjSiHw0sKU)   
[Marco](https://editor.p5js.org/malee21/present/h0Ssrwjb5)   
[Michaela](https://editor.p5js.org/michaela29/present/IY5W2TjE)   
[Katelyn](https://editor.p5js.org/jizhang6/full/60YQnrNv)   
[Curtis](https://editor.p5js.org/culee/present/QKntQP8Y)    
[Duan](https://editor.p5js.org/Duan25/present/cGVlVGgc)   
[Nikhita](https://editor.p5js.org/Bluesnow/full/pGp93tiu)   
 
