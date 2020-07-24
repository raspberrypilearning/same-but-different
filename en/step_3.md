## Develop first sprite's costumes

Now it's time to get your first sprite working with two costumes.

The sprite will `switch`{:class="block3looks"} costumes at the very beginning of the game so the user can see which sprite is the one they need to focus on.

--- task ---
Open and explore the first sprite's Costume tab.

If your first sprite has got a few costumes then delete all but the first costume. 

--- /task ---

--- task ---

Copy the first costume to create a second costume. The second costume will reveal the surprise.

**Add me in: generic-scratch-copy-costume-from-library**

--- /task ---

--- task ---
Rename the costumes so they are easy to recognise. For example, ChosenName1 and ChosenNameSurprise2.

**Add me in: generic-scratch-copy-costume-rename-from-library**

--- /task ---

--- task ---
Now add a surprise to the second cosutme. You could draw it in the Paint Editor or you may want to explore a graphic from another sprite's costumes. Have a thorough look at the costumes in Choose a Sprite. 

**Add me in: scratch-copyinggraphicFromCostume-costumes**

--- no-print ---
![Animated gif showing costume changing](images/character + doughnut + eyes.gif){:width="400px"}

--- /no-print ---
--- /task ---

--- task ---
Think about where in the Paint Editor you want the surprise to go.

Don't spend ages on the graphics. Graphics are really important but there's lots of coding to get on with as well!

--- /task ---

--- task ---
Here's the code the first sprite uses. You will decide on the values:

```blocks3
when flag clicked
set size to [ ] %` :: looks
go to x: ( ) y: ( )
+ switch costume to [your costume name 1 v]
wait ( ) seconds
+ switch costume to [your costume name 2 v]
wait ( ) seconds
+ switch costume to [your costume name 1 v]
wait (  ) seconds
broadcast [move v] and wait :: control
```

Read the code line by line to understand how it works using the `green flag clicked`{:class="block3events"}, `wait`{:class="block3control"} blocks and `switch costume to`{:class="block3looks"} blocks.

--- /task ---

--- task ---

Click on the Code tab of the frist sprite.

--- /task ---

--- task ---

Add code to make your sprite change costumes.

**Tip:** Don't forget to select the correct costume name for each `switch costume to`{:class="block3looks"} block from the dropdown to achieve your chosen sequence.

--- /task ---

--- task ---
Run your program to check it's working.

--- /task ---

--- task ---
Give the sprite a starting position on the Stage.

**Add me in: scratch-gotoxy-costumes**

--- /task ---

--- task ---
Is the sprite the size you want it to be? If not, adjust its size. Making the sprite smaller or bigger means they will look more in proportion in relation to the Backdrop. You can change the size of a sprite in two ways.

**Add me in: generic-scratch-change-sizeusinglooksblock&inspritearea**

--- /task ---

--- task ---
Run your program again to check it is working.

--- /task ---

--- task ---
At the very end of the program use a broadcast block which will let all the other sprites know that they can now begin their programs simultaneously.

--- /task ---

--- task ---
Your program should now look like the program above but with values filled in to suit your project. Trace your own code line by line before you run it. 

**Tip:** Code tracing is a good way to check how and if your program will work before running it.

--- /task ---

--- task ---

Now run your program again. Is it working as you had planned?

--- /task ---

*[Code tracing]: simulating the execution of code by hand in order to manually check that the code works correctly before you run it.

--- save ---


