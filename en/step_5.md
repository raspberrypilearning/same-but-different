## Repeat until not touching colour and edge

In the previous step you used a `repeat`{:class="block3control"} block to control the number of times the first sprite moves. 

You now need to make sure that the sprites will not end up layered on top of each other at the end of the `repeat`{:class="block3control"}. In this step, you will use the `repeat until`{:class="block3control"} to ensure the first sprite moves until it is `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites or the edge of the Stage.

The `not`{:class="block3operators"} block is a Boolean operator.

--- task ---
You need to select the `Operators`{:class="block3operators"} blocks `and`{:class="block3operators"} and `not`{:class="block3operators"}.

Create the code below:
```blocks3
repeat until <not < touching color () ? :: sensing  >:: operators > :: control
```
--- /task ---

```blocks3
<not < touching color () ? :: sensing  >:: operators > and <not < touching [edge v] ? :: sensing  >:: operators > 
```
--- task ---
Under the above block now copy and paste your `glide () secs to`{:class="block3motion"} etc block which you created especially for your animation in the`repeat`{:class="block3control"} block.

TRACY, DO WE NEED THE BELOW HOW TO?
**Add me in: scratch-copyblocksofcode or gif?**

UsiNG the same block will ensure that the first sprite's movement is unchanged whilst the block is waiting to be `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites.

--- /task ---

--- task ---
Pick the border or furthermost perimeter colour from your first costume. If there isn't one you will need to make one. If your sprite will move left asnd right you only need to choose the left/right perimeter colour. If the movement is random, you will need to create/choose the border colour around your first sprite.

The game will end when all the sprites are not touching this colour on each other.

**Add me in: scratch-creatingborder-costume**
**Add me in: scratch-color/saturation/brightness/eyedropper-sprite**

--- /task ---

--- task ---

ALSO INCLUDE DISTRACTOR INFO

--- /task ---

--- task ---

Run your code. Is it working? If not, you will need to debug!

TRACT, LIST OF POSSIBLE THINGS WHICH COULD BE INCORRECT?

**Add me in: scratch-debug**

--- /task ---

*[Boolean operator]: returns either of two possible values: true or false. The not operator can be used to turn a True into a False, or a False into a True i.e. if something is Not True it is False.

--- save ---

