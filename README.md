# csPortfolio

<details><summary><strong> My First WebPage!</strong></summary>
    <p>
       <a href="https://freskep.github.io/testWeb/dogPage/)
                </p>
* Lighting [here](https://freskep.github.io/lightning2/">Link<a>
* College Presentation [here](https://freskep.github.io/daDice/)
* Guitar Hero [here](https://freskep.github.io/daDice/)
* Dice [here](https://freskep.github.io/daDice/)
* Chemotaxis JS [here](https://freskep.github.io/chemotaxis4/pJS/index.html)
* Starfield [here](https://freskep.github.io/starfield5/index.html)
* Reflection on trimester 1
```Java

Tough code!  this was really hard to figure out for me.  This code allows a jumboParticle to bounce off the screen.  This is how it works:
-when x reaches the edge of the screen the speed variable flips direction
-same for y
-this creates a bouncing effect
-once it reaches the bottom corner of the screen it travels to the top right corner and repeats infinitely
void move {
x+=speed;
    y+=speed+1;
    if (x>width-25) {
      x=width-25;
      speed*=-1;
    }
    else if (x<0) {
      x=0;
      speed*=-1;
    }
    else if (y>height-25) {
      y=height-25;
      speed*=-1;
    }
    else if (y<0) {
      y=0;
      speed*=-1;
    }
   if (x<25 && y>400) {
      x=width-25;
      y=0;
      speed*=-1;
    }
      }
```
