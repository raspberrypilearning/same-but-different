## Variables

--- task ---
You need to set two variables: speed and finished.

**Tip:** Look inside the project [Focus on the prize](https://learning-admin.raspberrypi.org/en/projects/focus-on-the-prize) to refresh your memory of variables.

--- /task ---

## speed 
--- task ---

This variable needs to be ticked in the Blocks area so it appears as a graphic on the Stage. 

--- /task ---

--- task ---

When it is in the Stage, double-click on it until you reach the variable as a slide. The user will now be able to vary the speed they play the game themselves.

**scratch-variable-slider

--- /task ---

--- task ---
Add speed in secs in the `repeat`{:class="block3control"} and `repeat until`{:class="block3control"} blocks.

--- /task ---

--- task ---
Add this block under the `when green flag clicked`{:class="block3event"} block:

```blocks3
set [speed v] to () :: variables
```
Changing the value `1` will mean the game will start on whatever other value you give `speed`{:class="block3variables"}.

--- /task ---

## finished 
--- task ---
The `finished{`:class="block3variables"} variable acts as a switch set to `true`{:class="block3variables"} at the start of the game `when green flag clicked`{:class="block3event"}. At the end of the sequence, when the first sprite has shown its surprise costume and reverted back to its original costume, the `finished{`:class="block3variables"} variable switches to `true`{:class="block3variables"}.

```blocks3
set [finished v] to (true) :: variables
```
--- /task ---

--- task ---
Add this block as the very last block in `when green flag clicked`{:class="block3event"}:

```blocks3
set [finished v] to (false) :: variables
```
--- /task ---

In the next step you will use `false`{:class="block3variables"} to communicate to all the sprites next stage of the game.
