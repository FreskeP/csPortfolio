# Portfolio of Dreams

<details><summary><strong> My First WebPage!</strong></summary>
    <p>
       <a href="https://freskep.github.io/testWeb/dogPage/">MyFavoriteMovies<a>
           Making websites isn't very hard and it's really fun! This was a simple, fun way to start off the year.
                </p>
           </details>
 <details><summary><strong> A Little Lightning </strong></summary>
<p>   
<a href= "https://freskep.github.io/lightning2/">CickToGetShocked<a>
    I was very confused as to how the lightning project worked and this is very evident because it’s my worst one. I didn’t understand how the class functioned. Plus I sat alone so I didn’t get the chance to work with others. I struggled with the one.
    </p>
    </details>
 <details><summary><strong> College Presentation</strong></summary>
    <p>
<a href="https://docs.google.com/presentation/d/10lDlZwkgYPeKswM6w2SlBl-qigl4xleRxhesUL9dV8k">KnowledgeIsHere<a>
    I didn't enjoy this project, but I defintely understand why we did it.  It's helpful to get us thinking about our future and it's also helpful seeing what coding in the real world is like.  I learned a lot.
    </p>
    </details>

 <details><summary><strong> Deez Dice </strong></summary>
        <p>
    <a href="https://freskep.github.io/daDice/">ClickToShake<a>
        I felt this was the easiest one out of all the projects we did and I’m happy with how it turned out.  I didn’t do anything too interesting because I needed to keep moving, but I made a fully functional table of dice with a counter for each number.
        </p>
        </details>

<details><summary><strong> Some Craziness (starfield)</strong></summary>
                <p>
               <a href="https://freskep.github.io/starfield5/index.html">ClickToBeUnder-Impressed<a>
                I got a late start on this one and I’m kinda indifferent with the result.  I really like my jumbo particle bouncing around off the border of the screen and I also like the figure 8 pattern I got going but it’s overall kinda bland to look at.  Still the coolest looking one in my portfolio.  
                   </p>
                   </details>                   
   
   <details><summary><strong> Winter Wonderland </strong></summary>
<p>   
<a href= "https://freskep.github.io/HolidayCard2018/">Click4Joy<a>
    Me and a partner worked together on this beautiful christmas setpiece.  He contributed the snow effects.  I did the rest.  
    </p>
    </details> 
    
<details><summary><strong> Tri 3 Reflection</strong></summary>
                    <p>
                       
What is one or two things that are a source of pride in your programming development?  
-I'm proud that while i wasn't able to do every line of code on my own, I challenged myself with a tough project idea that I stuck with because it was really cool to me.

Identify them, write about why they are accomplishments, how you did it and what you learned.  Be sure to submit a code snippet along with your writing on the readMe file in your repo. <br/>

```Java
private TreeNode add(Comparable val, TreeNode tree) {
    if (tree == null)
      tree = new TreeNode(val);

    Comparable treeValue = tree.getValue();
    int dirTest = val.compareTo(treeValue);    

    if (dirTest < 0)
      tree.setLeft(add(val, tree.getLeft()));
    else if (dirTest > 0)
      tree.setRight(add(val, tree.getRight()));

    return tree;
  }
       
   
   <br/>
   
I honestly dont fully understand the ins and outs of trees, but it was still cool to see how more complex data structures are used. 

```

-Identify the most significant hurdle you encountered last trimester.  Write about what it was and how it was resolved.

I struggled comprehending the new intense concepts we were introduced to this trimester.  I tried no to feel like it was too much to handle and i tried to push through.  I resolved it by not giving up and learning from people who grasp the concepts.

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

Tough code!  this was really hard to figure out for me. I had to get a couple friends to work with me to make it happen.  It required the appliction of Calculus.  The code uses the unit circle to allow the Runne object to rotate around the curves of the track.  It utilyzes an "angle" variable that is changed based on its location using polar values, not standard x and y values.


      if (xLoc>=758 && xLoc<=945 && angle<=(PI/2)) {
        angle+=(PI/120);
        xLoc+=-4.75*sin(angle);
        yLoc-=4.275*cos(angle);
        
      }

      //backstretch
      if (xLoc>230 && xLoc<=755 && yLoc<400) {
        xLoc-=2;
      }

      //second curve

      if (xLoc<=230 && xLoc>=50 && angle<=((3*PI)/2)) {
        angle+=(PI/120);
        xLoc+=-4.75*sin(angle);
        yLoc-=4.275*cos(angle);
      }

      //homestretch
      if (xLoc>=229 && xLoc<=758 && yLoc>400) {
        xLoc+=2;
      }
      if (xLoc==757&&yLoc==507) {
        angle=(-PI/2);
        
      }
      if (angle==(4.686209)) {
        xLoc=758;   
        yLoc=507;
        angle=(-PI/2);  
        
        println(lapCount);
      }
```
<details><summary><strong> Cheeky Chemotaxis</strong></summary> 
            <p>   
            <a href="https://freskep.github.io/chemotaxis4/pJS/index.html">ClickToShootHoops<a>
                This is the lab the got me really behind.  I struggled a lot right away because I just didn’t know where to begin problem solving.  Again, I sat alone so I had no one to assist me.  I ended up doing something that isn’t the exact idea you wanted from us, but still sorta counts as chemotaxis in a way.  I got even more behind when a little error halted all progress for a a little over a day.  But finally solving the issue without any help was extremely satisfying.  
                </p>
                </details>    
                
![logo](/images/chemot.png)    

  <details><summary><strong> Race of the Ages </strong></summary>
<p>   
<a href= "https://freskep.github.io/TrackSim/">ClickFORaRACE<a>
   Really fun lab that utilyzes calculus, maps, and file parsing.  Never reached its full potential.
    </p>
    </details>   
    
![logo](/images/sim.png)   

<details><summary><strong> A Little Lightning </strong></summary>
<p>   
<a href= "https://freskep.github.io/lightning2/">CickToGetShocked<a>
    I was very confused as to how the lightning project worked and this is very evident because it’s my worst one. I didn’t understand how the class functioned. Plus I sat alone so I didn’t get the chance to work with others. I struggled with the one.
    </p>
    </details>

![logo](/images/lightning.png) 
