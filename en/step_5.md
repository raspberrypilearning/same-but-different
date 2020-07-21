## Repeat until not touching colour

You created a `repeat`{:class="block3control"} to control the number of times the first sprite moves. In order to make sure that the sprites do not end up layered on top of each other at the end of their movement, you will now use Boolean. You will use a `repeat until`{:class="block3control"} block to ensure the first sprite moves until it is `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites. 

--- task ---
Create the code below:
```blocks3
repeat until <not < touching color () ? :: sensing  >:: operators > :: control
glide () secs to x: () y: () :: motion
```
--- /task ---

--- task ---
Pick the border or perimeter colour from your first costume. The game will end when the sprites are not touching this colour on each other.

--- /task ---

--- task ---
Add  the block of code underneath the repeat block.
--- /task ---

TRACY, DO WE NEED THE BELOW HOW TO?
**Add me in: scratch-color/saturation/brightness/eyedropper-sprite**

*[Boolean]: returns either of two possible values: true or false. The not operator can be used to turn a True into a False, or a False into a True i.e. if something is Not True it is False.

--- save ---

