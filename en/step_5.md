## Repeat until not touching colour

In the previoous step you used a `repeat`{:class="block3control"} block to control the number of times the first sprite moves. 

In order to make sure that the sprites do not end up layered on top of each other at the end of their movement, in this step you will now not Boolean operator. You will use a `repeat until`{:class="block3control"} block to ensure the first sprite moves until it is `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites. 

--- task ---
Create the code below:
```blocks3
repeat until <not < touching color () ? :: sensing  >:: operators > :: control
```
--- /task ---

--- task ---
Under the above block now copy and place your `glide () secs to x: () y: ()`{:class="block3motion"} which you created in the `repeat`{:class="block3control"} block.

TRACY, DO WE NEED THE BELOW HOW TO?
**Add me in: scratch-copyblocksofcode or gif?**

This will ensure that the first sprites movement is unchanged whilst the block is waiting to be `not`{:class="block3operators"} `touching`{:class="block3sensing"} any of the other sprites. 
--- /task ---

--- task ---
Pick the border or perimeter colour from your first costume. The game will end when the sprites are not touching this colour on each other.

--- /task ---

--- task ---
Add your block of code underneath the repeat block.

TRACY THIS SEEMS THE CONFUSING BIT!

--- /task ---

--- task ---
Run your code. Is it working
--- /task ---

TRACY, DO WE NEED THE BELOW HOW TO?
**Add me in: scratch-color/saturation/brightness/eyedropper-sprite**

*[not Boolean operator]: returns either of two possible values: true or false. The not operator can be used to turn a True into a False, or a False into a True i.e. if something is Not True it is False.

--- save ---

