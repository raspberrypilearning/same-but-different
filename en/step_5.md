## When I receive move
Now that the costumes on the first sprite are switching and you have broadcast at the end of the costume sequence you can add movement to the first sprite under a `when I receive`{:class="block3control"} block.

--- task ---
Think about how you want your sprites to move. The sprites need to move in the same way so that the sprite with the surprise is harder to identify.  
--- /task ---

--- task ---
Look at the Backdrop you have chosen and explore how your sprites might move in relation to it. 

Look at the movement of the sprites in these Same but different project examples:

![Complete project](images/same_triplets.gif)
![Complete project](images/same_hens.gif)
![Complete project](images/same_presents.gif)

**Tip:** Linking a sprite's motion to the backdrop graphic will make your project more realistic.

--- /task ---

--- task ---
In the first sprite's Costume tab, make sure the first costume is selected. Now the game will always start with the first costume.

**Add me in: scratch-selectcostumetoshowfirsteitherusingshoworbclickingonit**

--- /task ---

--- task ---
Try out different sprite motion to help you decide which movement is best for your first sprite.

**Add me in: scratch-movesprite**

--- /task ---

--- task ---
For a reminder of the code required under the `when I receive`{:class="block3control"} block explore the code in the [Which triplet ate the doughnut?](https://scratch.mit.edu/projects/411558897/editor){:target=”_blank”} project.
--- /task ---

--- task ---
Adjust the values of `repeat`{:class="block3control"} and `secs`{:class="block3motion"} and run the program until you are happy with the pace of the sprite. It often takes a few attempts to get a sprite animating in a way that you are happy with.

--- /task ---

--- task ---
Run your program.

--- /task ---

--- task ---
Instead of a fixed number of seconds, you can vary the speed that the first sprite moves by adding a `variable`{:class="block3variables} called `speed`{:class="block3variables} to the `secs`{:class="block3motion"} block.

You are  going to make a slider for the speed variable so that the user can modify the speed easily when they are playing the game. 

**Add me in: scratch-variables+slider+values**

--- /task ---

--- task ---

You can adapt the `x`{:class="block3motion"} and `y`{:class="block3motion"} coordinates to create more specfic sprite movement.

**Add me in: scratch-movespriteusingOperators**

For example, in [Which triplet ate the doughnut?](https://scratch.mit.edu/projects/411558897/editor/), the sprites have a random `x`{:class="block3motion"} value and a fixed `y`{:class="block3motion"} value so that the triplets appear to be gliding along the pavement.

**Add me in: scratch-randomcoordinates**

--- /task ---

You have  used a `repeat`{:class="block3control"} block to control the number of times the first sprite moves. 

--- task ---
You now need to make sure that the sprites will not end up layered on top of each other. To do this, you will use the `repeat until`{:class="block3control"} to ensure the first sprite moves until it is `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites or the edge of the Stage.

For this, you will use the Boolean `Operators`{:class="block3operators"} of `and`{:class="block3operators"} and `not`{:class="block3operators"}.

**Add me in: scratch-and-not-operators**

--- /task ---

--- task ---
Under the above block, copy and paste the `motion`{:class="block3motion"} block which you created within the`repeat`{:class="block3control"} block. Using the same block will ensure that the first sprite's movement is unchanged whilst the sprite is waiting to `not`{:class="block3operators"} be `touching`{:class="block3sensing"} any of the other sprites.

**Add me in: scratch-copyblocksofcode**

OR gif?

--- /task ---

The game will end when all the sprites are `not`{:class="block3operators"} `touching`{:class="block3sensing"} each other using  the `sensing`{:class="block3sensing"} block which can detect colour.

--- task ---
Pick the border or furthermost perimeter colour from your first sprite's, first costume. If there isn't a border you may need to make one.

**Add me in: scratch-colornottouching-costume**
**Add me in: scratch-creatingborder-costume**
**Add me in: scratch-color/saturation/brightness/eyedropper-sprite**

--- /task ---

--- task ---

Run your code. Is it working? If not, you will need to debug!

--- /task ---

--- task ---

Identify what is not working and which sprite it relates to. You may need to run the program a number of times to identify the issue.

**Tip:**: Ask a friend to check your code. It's sometimes easier to pick up errors if you are new to a program.

**Add me in: scratch-debug**

--- /task ---

--- task ---

Tidy up and resize your programs within the Code tab. It will be easier to see all the seperate programs as you develop more.

**Add me in: scratch-cleanupBlocks&magnifier-organiseCodetab**

--- /task ---
*[Boolean operator]: returns either of two possible values: true or false. The not operator can be used to turn a True into a False, or a False into a True i.e. if something is Not True it is False.


--- save ---
