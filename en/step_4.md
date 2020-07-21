## When I receive move
You've got the costumes changing the way you want them to on the first sprite. Now you can add movement to the first sprite.

Let's get the first sprite moving randomly within the stage. Then you can modify your code to make your sprite move more specifically.

--- task ---

Go to the first sprite's Code tab and add the following blocks:

```blocks3
when I receive [move v] :: event
repeat ():: control
glide () secs to [random position v] :: motion
```

Decide how many times you want the first sprite to `repeat`{:class="block3control"} gliding to a random position and how many `seconds`{:class="block3motion"} you want it to glide for.

--- /task ---

--- task ---
Run your program.

**Tip:**: Adjust the values of `repeat`{:class="block3control"} and `seconds`{:class="block3motion"} and run the program until you are happy with the pace of the sprite. It often takes a few attempts to get the sprite animating in a way that you are happy with.

--- /task ---

--- task ---

Tidy up and resize your program within the Code tab. It will be easier to see first sprite's program as it gets longer.

**Add me in: scratch-cleanupBlocks&magnifier-organiseCodetab**

--- /task ---

--- task ---
Instead of a fixed number of seconds, you can vary the speed that the first sprite moves by adding a `varible`{:class="block3variables} called `speed`{:class="block3variables}. This will enable the user to increase or decrease the `seconds`{:class="block3motion"} block which will make their focus more or less  challenging.

You are also going to make a slider for the speed variable so that the user can modify the speed easily when they are playing the game.

**Add me in: scratch-variables+slider**

--- /task ---

--- task ---

You can replace the `glide () secs to random position`{:class="block3motion"} to create more specfic x and y coodinates for the first sprite. You can change the block to:
```blocks3
glide () secs to x: () y: () :: motion
```
Go to the Operators block and select `pick randon () to ()`{:class="block3operators"} 

You can choose  to may the  x or y coordinate random:
```blocks3
glide () secs to (pick random  ()  to ()  :: operators ) y: () :: motion
```
OR
```blocks3
glide () secs to x: () (pick random  ()  to ()  :: operators )  :: motion
```

Duplicate your first sprite to create the starting point for your next sprite.

**Add me in: scratch-duplicating-sprite**

--- /task ---

--- task ---

Change the new sprite's costume or edit the costume with the paint editor so that it looks different from your first sprite. 

**Add me in: scratch-paint-tool-basics**


--- /task ---

--- task ---
Think about how this sprite will be different to the first sprite. 

How big should the sprite be? 
Which direction will it point in?

Will the sprite appear behind or in front or other sprites?
**Add me in: generic-scratch-layers**

Try different movement patterns: 

**Add me in: generic-scratch-spin-around**

**Add me in: generic-move-in-a-circle**

--- /task ---


--- task ---
Make sure you have selected the sprite that you want to change and click on the Code tab.

Change the code so that the new sprite does what you want it to.

--- /task ---

--- task ---
If you have time, you can keep adding more sprites. Make each one different to the others. 

--- /task ---

--- save ---

