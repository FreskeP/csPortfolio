# csPortfolio

<details><summary><strong> My First WebPage!</strong></summary>
    <p>
       <a href="https://freskep.github.io/testWeb/dogPage/">SUPER<a>
                </p>
           </details>
 <details><summary><strong> A Little Lightning </strong></summary>
<p>
<a href= "https://freskep.github.io/lightning2/">Link<a>
    </p>
    </details>
 <details><summary><strong> College Presentation</strong></summary>
    <p>
<a href="https://freskep.github.io/daDice/">Link<a>
    </p>
    </details>
 <details><summary><strong> Deez Dice </strong></summary>
        <p>
    <a href="https://freskep.github.io/daDice/">Link<a>
        </p>
        </details>
 <details><summary><strong> Cheeky Chemotaxis</strong></summary>
            <p>
            <a href="https://freskep.github.io/chemotaxis4/pJS/index.html">Link<a>
                </p>
                </details>
<details><summary><strong> Some Craziness (starfield)</strong></summary>
                <p>
               <a href="https://freskep.github.io/starfield5/index.html">Link<a>
                   </p>
                   </details>
<details><summary><strong> Tri 1 Reflection</strong></summary>
                    <p>
                        Reflect on all your portfolio projects: <br/> <br/>
-lightning: I was very confused as to how the lightning project worked and this is very evident because it’s my worst one.  I didn’t understand how the class functioned.  Plus I sat alone so I didn’t get the chance to work with others.  I struggled with the one. 

-dice: I felt this was the easiest one out of all the projects we did and I’m happy with how it turned out.  I didn’t do anything too interesting because I needed to keep moving, but I made a fully functional table of dice with a counter for each number.  

-chemotaxis:  This is the lab the got me really behind.  I struggled a lot right away because I just didn’t know where to begin problem solving.  Again, I sat alone so I had no one to assist me.  I ended up doing something that isn’t the exact idea you wanted from us, but still sorta counts as chemotaxis in a way.  I got even more behind when a little error halted all progress for a a little over a day.  But finally solving the issue without any help was extremely satisfying.  

-starfield: I got a late start on this one and I’m kinda indifferent with the result.  I really like my jumbo particle bouncing around off the border of the screen and I also like the figure 8 pattern I got going but it’s overall kinda bland to look at.  Still the coolest looking one in my portfolio.  

 
What is one or two things that are a source of pride in your programming development?  
-I’m proud that every piece of code is my own or you helped me with it.  While my code is very complicated or sophisticated, I don’t take it from anyone sitting near me, nor do I take it off the internet.   This makes the end product more satisfying.

Identify them, write about why they are accomplishments, how you did it and what you learned.  Be sure to submit a code snippet along with your writing on the readMe file in your repo. <br/>

```Java
void draw()
{
 
  background(60);
   for (int r=0; r<1200; r=r+100) {
    for (int c=0; c<500; c=c+100) {
      die=new Die(r, c);
       die.display();
       
   
   <br/>
   
This is in no way complicated code, and it isn’t the toughest bit <br/>of code i utilized in my projects either but this stands out to me<br/> because I was really happy that it worked when I first tried it<br/> because it took me a little bit to think of a way to get <br/> a bunch of dice on the screen without using an array. <br/> The syntax was what threw me off. 

```

-Identify the most significant hurdle you encountered last trimester.  Write about what it was and how it was resolved.

I was struggling a lot on the projects and felt extremely far behind everyone else in the class.  This was in part because I sat alone in a row and also because I didn’t do much outside of class.  I thought of this class as class where a lot of the work is done in school.  Once I realized I was falling behind I sought to fix this as quick as possible.  I did this by switching seats and doing more outside class.  This helped me a lot and I am significantly more productive in class now.

-Describe the incremental and iterative development process of your included code, focusing on two distinct points in that process. Describe the difficulties and/ or opportunities you encountered and how they were resolved or incorporated. In your description clearly indicate whether the development described was collaborative or independent. At least one of these points must refer to independent program development
<br/> 
A lot of times it goes sorta like this: 
<br/>
1. Take a minute and think about what I need to accomplish 
<br/>2. Begin typing my solution 
<br/>3. Realize an error in my idea
<br/>4. Be stumped for a while
<br/>5. Take another step back and I usually come up with part of the solution
<br/>6. Ask someone for help finishing my thoughts.  I typically start out this question like, “hey, I know I have to do blah blah blah… but I’m kinda confused about how I should go about it.”
<br/>7. Complete the problem!
<br/>This is especially the case in projects like Starfield/chemotaxis when I spend a day or two working on a single element of my project.
</p>
</details>
                        
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
