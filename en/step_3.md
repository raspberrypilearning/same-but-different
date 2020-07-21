## Develop sprite costumes
TRACY, USER OR PLAYER?

Now it is time to get your first sprite working with two costumes. You will start with the first sprite with the surprise and then add more. 

The first sprite will `switch`{:class="block3looks"} costumes at the beginning of the game so the user can see which sprite it the one they're meant to be focusing on.

--- task ---
Copy the sprite's first costume to create a second surprise costume.

**Add me in: generic-scratch-copy-costume-from-library**

Now add a surprise to the second costume but don't spend ages on the graphics. Graphics are really important but there's lots of coding to get on with as well!

Think about how you want your sprite to be animated. For example, you might say:
+ "I want my sprite to reveal the surprise from inside itself" (for example, like a doughnut in the character's stomach)
+ "I want my sprite to reveal the surprise from outside itself" (for example, like the idea doughbut, hovering above the character)
+ and even "I want my sprite to also react to the surprise" (for example, character's eyes looking up at the idea doughnut).

--- /task ---

--- task ---
Rename the costumes so they are easy to recognise. For example, ChosenName1, ChosenNameSurprise2 etc.

**Tip:** Naming AND numbering your costumes is often a good way to remember the order of your costumes.

--- /task ---

When the `green flag clicked`{:class="block3events"}, the sprite changes from its first costume to its second surprise costume and then back to its first costume  again. You may create a third costume later but we don't need to think about that for now.

TRACY, HOW SHOULD THE BELOW EXAMPLES WORK?

--- no-print ---

![Animated gif showing costume changing](images/character + doughnut + eyes.gif){:width="400px"}

--- /no-print ---

--- print-only ---

![Image annotated with costume changing](images/character + doughnut + eyes.gif){:width="400px"}

--- /print-only ---

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
Click on the Code tab of the first sprite.

--- /task ---

--- task ---
Add code to make your sprite change costumes. Don't forget to add `wait`{:class="block3control"} blocks between each `switch`{:class="block3looks"} costume block.

In your project, don't forget to select from the dropdown the correct costume name for each `switch`{:class="block3looks"} costume block to create your chosen animation.

--- /task ---

--- task ---
Give the first sprite a starting position. The place you want your first sprite to start will vary according to your project idea. For instance, in [Which Triplet ate the doughnut?](https://scratch.mit.edu/projects/411558897) the starting position of the first sprite is set so the sprite appears to stand on the ground of the backdrop.

**Tip:** if you drag the first sprite to the position you want it to start in you will notice that the `go to x: () y: ()`{:class="block3motion"} will automatically register the coordinates. You can then simply drag the block to the correct position without having to type in the coordinates.

```blocks3
go to x: ( ) y: ( )
```
Place the `go to x: () y: ()`{:class="block3motion"} block below the `green flag clicked`{:class="block3events"}.
--- /task ---

--- task ---
Run your program to check it is working.

TRACY, ANYMORE ON DEBUGGING?

--- /task ---

--- task ---
Is your sprite the size you want it to be? If not, adjust its size.

**Add me in: generic-scratch-change-size **

Place the `set size to ( ) %`{:class="block3looks"} block between the `green flag clicked`{:class="block3events"} and the `go to x: () y: ()`{:class="block3motion"}  blocks.

--- /task ---

--- task ---
At the end of the program you can now add a broadcast block which will let all the sprites (when you create them) know that they can now begin their programs simultaneously.

```blocks3
broadcast [move v] and wait :: control
```

--- /task ---

--- task ---
Your program should now look like the below but with values filled in to suit your project. Trace the code line by line before you run it. Code tracing is a good way to check how, as well as if, your program will work before running it:

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

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---

*[code tracing]: simulating the execution of code by hand in order to manually check that the code works correctly before you run it.

