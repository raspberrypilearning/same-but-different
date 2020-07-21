## Develop a sprite's costume FROM Get a sprite moving
TRACY, USER OR PLAYER?

Now it is time to get your first sprite working with two costumes. You will start with the first sprite with the surprise and then add more. 

The first sprite will `switch`{:class="block3looks"} costumes at the beginning of the game so the user can see which sprite it the one they're meant to be focusing on.

--- task ---
Copy the sprite's first costume to create a second surprise costume.

**Add me in: generic-scratch-copy-costume-from-library**

--- /task ---

When the `green flag clicked`{:class="block3contol"}, the sprite changes from its first costume to its second surprise costume and then back again to the first costume.

--- no-print ---
![Animated gif showing costume changing](images/character + doughnut + eyes.gif){:width="400px"}
--- /no-print ---

--- print-only ---
![Image annotated with path of sprite](images/moving-up-down.png){:width="400px"}
--- /print-only ---

Here's the code it uses:

```blocks3
when flag clicked
+ switch costume to [character1 v]
wait (1) seconds
+ switch costume to [character2 v]
wait (2) seconds
+ switch costume to [character1 v]
```
Look at the code and understand how it makes the costumes change.

--- /task ---

--- task ---
Now add a surprise to the second costume. Don't spend ages on the graphics. Graphics are really important but there's lots of coding to get on with as well!

Think about how you want your sprite to be animated. For example, you might say "I want my sprite to reveal the surprise from inside itself" (doughnut in tummy), "I want my sprite to reveal the surprise from outside itself" (idea doughnut), and/or "I want my sprite to react to the surprise" (character's eyes following idea doughnut).

--- /task ---

--- task ---
Select your first sprite and click on its Code tab. 

--- /task ---

--- task ---
Add code to make your sprite change costume.

In your project, don't forget to select from the dropdown the correct costume names within the `switch`{:class="block3looks"} costume block to create your chosen animation. 


--- /task ---

--- task ---
To start with, give the first sprite a starting position. The place you want your first sprite to start will vary according to your project  idea. For instance, in [Which Triplet ate the doughnut?](https://scratch.mit.edu/projects/411558897) the starting position of the  first sprite is set so it appears to stand on the ground of the backdrop.

```blocks3
go to x: (150) y: (0)
```

--- /task ---

--- task ---
At the end of the  program now add a broadcast block to let all the sprites know that they can now begin their programs.

```blocks3
broadcast [move v] and wait :: control
```

--- /task ---

--- task ---
Is your sprite the size you want it to be? If not, adjust its size.

**Add me in: generic-scratch-change-size **

--- /task ---

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---
