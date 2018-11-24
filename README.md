# csPortfolio

* WebPage [here](https://freskep.github.io/testWeb/dogPage/)
* Lighting [here](https://freskep.github.io/lightning2/)
* College Presentation [here](https://freskep.github.io/daDice/)
* Guitar Hero [here](https://freskep.github.io/daDice/)
* Dice [here](https://freskep.github.io/daDice/)
* Chemotaxis JS [here](https://freskep.github.io/chemotaxis4/pJS/index.html)
* Starfield [here](https://freskep.github.io/starfield5/index.html)
```Java
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
