## Get a sprite moving
Now it is time to get your first sprite working with its costumes. You will start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop. 

--- task ---
When the `green flag clicked`{:class="block3contol"}, the sprite changes from its original costume to a surprise costume and then back again. You will need to select the correct costume names for your project. Note,  the surprise costume is

--- no-print ---
![Animated gif showing costume changing](images/moving-up-down.gif){:width="400px"}
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

Look at the code and understand how it makes the sprite move.

Choosing `0` in the `point in direction`{:class="block3motion"} block makes the sprite point upwards so the `move`{:class="block3motion"} block will make the sprite move up to the top of the stage. If the sprite touches the top of the Stage it will flip direction and start moving down towards the bottom of the stage. 

--- /task ---

--- task ---
Think about how you want your sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly." or "I want my sprite to be really small and move quickly in a diagonal line."
--- /task ---

--- task ---
Select your first sprite and click on the Code tab. 

--- /task ---

--- task ---
Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage. 

**Add me in: generic-scratch-if-on-edge-bounce **

--- /task ---

--- task ---
Change the speed and direction of your sprite to get the effect you want. 

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
