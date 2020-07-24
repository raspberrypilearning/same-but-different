## Develop sprite costumes

Now it's time to get your first sprite working with two costumes. You will start with the first sprite and then add more. 

The sprite will `switch`{:class="block3looks"} costumes at the very beginning of the game so the user can see which sprite is the one they need to focus on.

--- task ---
Open and explore the first sprite's Costume tab.

If your first sprite has got a number of costume delete all but the first costume. Then, copy the first costume to create a second costume.

**Add me in: generic-scratch-copy-costume-from-library**

--- /task ---

--- task ---
Rename the costumes so they are easy to recognise. For example, ChosenName1, ChosenNameSurprise2 etc.

--- /task ---

--- task ---
Add a surprise to the second cosutme. You could draw it in the Paint Editor or you may want to explore a graphic from other sprite costumes. Have a thorough look at the costumes in Choose a Sprite. 

**Add me in: scratch-copyinggraphicFromCostume-costumes**

--- no-print ---
![Animated gif showing costume changing](images/character + doughnut + eyes.gif){:width="400px"}

--- /no-print ---

--- task ---
Think about where in the Paint Editor you want your surprise to go.

Don't spend ages on the graphics. Graphics are really important but there's lots of coding to get on with as well!

--- /task ---

--- task ---
Here's the code the first sprite uses:

```blocks3
when flag clicked
+ switch costume to [Costume1 v]
wait (1) seconds
+ switch costume to [CostumeSurprise2 v]
wait (2) seconds
+ switch costume to [Costume1 v]
wait (2) seconds
```
Look at the code and understand how it makes the costumes change.

--- /task ---

--- task ---

Click on the Code tab of the sprite.

--- /task ---

--- task ---

Add code to make your sprite change costumes using the `green flag clicked`{:class="block3events"}, `wait`{:class="block3control"} blocks and `switch costume to`{:class="block3looks"} blocks.

**Tip:** Don't forget to select the correct costume name for each `switch costume to`{:class="block3looks"} block from the dropdown to achieve your chosen sequence.

--- /task ---

--- task ---
Run your program to check it's working.

--- /task ---

--- task ---
Give the sprite a starting position on the Stage.

**Add me in: scratch-gotoxy-costumes**

Place the `go to x: () y: ()`{:class="block3motion"} block below the `green flag clicked`{:class="block3events"} block.
--- /task ---

--- task ---
Is the sprite the size you want it to be? If not, adjust its size. You can change the size of a sprite in two ways.

**Add me in: generic-scratch-change-sizeusinglooksblock&inspritearea**

Place the `set size to ( ) %`{:class="block3looks"} block above or below the `go to x: () y: ()`{:class="block3motion"}  block. It will work either way. 

--- /task ---

--- task ---
Run your program again to check it is working.

--- /task ---

--- task ---
At the very end of the program use a broadcast block which will let all the other sprites (when you create them) know that they can now begin their programs simultaneously.

```blocks3
broadcast [move v] and wait :: control
```

--- /task ---

--- task ---
Your program should now look like the below but with values filled in to suit your project. Trace the code line by line before you run it. Code tracing is a good way to check how and if your program will work before running it:

```blocks3
when flag clicked
set size to [ ] %` :: looks
go to x: ( ) y: ( )
+ switch costume to [Costume1 v]
wait ( ) seconds
+ switch costume to [CostumeSurprise2 v]
wait ( ) seconds
+ switch costume to [Costume1 v]
wait (  ) seconds
broadcast [move v] and wait :: control
```

--- /task ---

--- task ---

Now run your program. Is it working as you had planned?

--- /task ---

--- save ---

*[Code tracing]: simulating the execution of code by hand in order to manually check that the code works correctly before you run it.

