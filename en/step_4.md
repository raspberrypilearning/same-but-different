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

Decide how many times you want the first sprite to `repeat`{:class="block3control"} gliding to a random position and how many `secs`{:class="block3motion"} (seconds) you want it to glide for.

--- /task ---

--- task ---
Run your program.

**Tip:**: Adjust the values of `repeat`{:class="block3control"} and `secs`{:class="block3motion"} and run the program until you are happy with the pace of the sprite. It often takes a few attempts to get a sprite animating in a way that you are happy with.

--- /task ---

--- task ---
Instead of a fixed number of seconds, you can vary the speed that the first sprite moves by adding a `variable`{:class="block3variables} called `speed`{:class="block3variables}. This will enable the user to increase or decrease the `seconds`{:class="block3motion"} block which will make their focus more or less  challenging.

You are also going to make a slider for the speed variable so that the user can modify the speed easily when they are playing the game.

**Add me in: scratch-variables+slider**

--- /task ---

--- task ---

You can replace the `glide () secs to random position`{:class="block3motion"} with another `Motion`{:class="block3motion"} block to create more specfic x and y coodinates for the first sprite. You can change the block to:
```blocks3
glide () secs to x: () y: () :: motion
```
And select from the `Operators`{:class="block3operators"} block `pick random () to ()`{:class="block3operators"}.

The `pick random () to ()`{:class="block3operators"} will enable you to choose random coordinates for either the x or y. For instance:

```blocks3
glide () secs to (pick random  ()  to ()  :: operators ) y: () :: motion
```
OR
```blocks3
glide () secs to x: () (pick random  ()  to ()  :: operators )  :: motion
```
In [Which triplet ate the doughnut](https://scratch.mit.edu/projects/411558897/editor/) the first sprite has a randon x  value and a fixed y value so the triplets move alond  the same y path so they appear to be gliding along the pavement.

**Tip:**: Linking a sprite's motion to the backdrop graphics can make your project more realistic.

TRACY, DO WE NEED THIS?
**Add me in: scratch-randomcoordinates**

--- /task ---

--- task ---

Tidy up and resize your program within the Code tab. It will be easier to see first sprite's program as it gets longer.

**Add me in: scratch-cleanupBlocks&magnifier-organiseCodetab**

--- /task ---

--- save ---
