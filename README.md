# csPortfolio

<details><summary><strong> My First WebPage!</strong></summary>
    <p>
       <a href="https://freskep.github.io/testWeb/dogPage/">Link<a>
                </p>
           </details>
* <details><summary><strong> A Little Lightning </strong></summary>
<p>
<a href= "https://freskep.github.io/lightning2/">Link<a>
    </p>
    </details>
* <details><summary><strong> College Presentation</strong></summary>
    <p>
<a href="https://freskep.github.io/daDice/">Link<a>
    </p>
    </details>
* <details><summary><strong> Deez Dice </strong></summary>
        <p>
    <a href="https://freskep.github.io/daDice/">Link<a>
        </p>
        </details>
* <details><summary><strong> Cheeky Chemotaxis</strong></summary>
            <p>
            <a href="https://freskep.github.io/chemotaxis4/pJS/index.html">Link<a>
                </p>
                </details>
* <details><summary><strong> Some Craziness (starfield)</strong></summary>
                <p>
               <a href="https://freskep.github.io/starfield5/index.html">Link<a>
                   </p>
                   </details>
* <details><summary><strong> Tri 1 Reflection</strong></summary>
                    <p>
                        
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
