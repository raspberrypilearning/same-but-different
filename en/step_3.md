## Develop a sprite's costume FROM Get a sprite moving
TRACY, USER OR PLAYER?

Now it is time to get your first sprite working with two costumes. You will start with the first sprite with the surprise and then add more. 

The first sprite will `switch`{:class="block3looks"} costumes at the beginning of the game so the user can see which sprite it the one they're meant to be focusing on.

--- task ---
Copy the sprite's first costume to create a second surprise costume.

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
+ go to x: (150) y: (0)
switch costume to [character1 v]
wait (1) seconds
switch costume to [character2 v]
wait (2) seconds
switch costume to [character1 v]
```
Look at the code and understand how it makes the costumes change.

--- /task ---

--- task ---
Now add a surprise to the second costume. Don't spend ages on the graphics. Graphics are really important but there's lots of coding to get on with as well!

Think about how you want your sprite to be animated. For example, you might say "I want my sprite to reveal the surprise from inside itself" (doughnut in tummy), "I want my sprite to reveal the surprise from outside itself" (idea doughnut), and/or "I want my sprite to react to the surprise" (character's eyes following idea doughnut).

In your project, will need to select the correct costume names within the `switch`{:class="block3looks"} costume block to create your chosen animation. 
--- /task ---

--- task ---
Select your first sprite and click on the Code tab. 

--- /task ---

--- task ---
Add code to make your sprite change costume.

--- /task ---

--- task ---
To start with, give the first sprite a starting position.


Add a broadcast block to let all the sprites and direction of your sprite to get the effect you want. 

--- /task ---

--- task ---
You may need to change the way your sprite's costume rotates when it moves to stop it going upside down.

**Add me in: scratch-rotate-costume **

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
