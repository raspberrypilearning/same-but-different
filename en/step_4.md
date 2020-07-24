## When I receive move
Now the costumes on the first sprite are now changing in the way you want you can add movement to the first sprite.

Think about how you want your sprite to move. 

--- task ---
Look at the Backdrop you have chosen and explore how the sprites might move in relation to it. 

Look at the movement of the sprites in three different projects.

![Complete project](images/same_triplets.gif)
![Complete project](images/same_hens.gif)
![Complete project](images/same_presents.gif)

--- /task ---

--- task ---
In the Costume tab, make sure you have selected the first costume.
--- /task ---

--- task ---
Now go to the first sprite's Code tab.

Trying out different movement will help you decide which is best for your sprite.

**Add me in: scratch-movesprite**

--- /task ---

--- task ---
Adjust the values of `repeat`{:class="block3control"} and `secs`{:class="block3motion"} and run the program until you are happy with the pace of the sprite. It often takes a few attempts to get a sprite animating in a way that you are happy with.

--- /task ---

--- task ---
Run your program.

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
For example, in [Which triplet ate the doughnut?](https://scratch.mit.edu/projects/411558897/editor/) the first sprite has a randon x  value and a fixed y value so the triplets move alond  the same y path so they appear to be gliding along the pavement.

**Tip:**: Linking a sprite's motion to the backdrop graphics can make your project more realistic.

TRACY, DO WE NEED THIS?
**Add me in: scratch-randomcoordinates**

--- /task ---

--- task ---

Tidy up and resize your program within the Code tab. It will be easier to see first sprite's program as it gets longer.

**Add me in: scratch-cleanupBlocks&magnifier-organiseCodetab**

--- /task ---

--- save ---
