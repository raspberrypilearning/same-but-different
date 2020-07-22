## Variables

--- task ---
You need to set two variables: `speed`{:class="block3variables"} and `finished`{:class="block3variables"}.

**Tip:** Refresh your memory of variables by seeing inside the project [Focus on the prize](https://learning-admin.raspberrypi.org/en/projects/focus-on-the-prize).

--- /task ---

## `speed`{:class="block3variables"}
--- task ---

The `speed`{:class="block3variables"} variable needs to be ticked in the Blocks area so it appears as a graphic on the Stage. 

--- /task ---

--- task ---

When the `speed`{:class="block3variables"} is in the Stage, double-click on it until you reach the variable as a slider. With a slider the user will now be able to vary the speed as they play the game themselves.

**scratch-variable-slider

--- /task ---

--- task ---
Add the  `speed`{:class="block3variables"} rounded block in the secs in the `repeat`{:class="block3control"} and `repeat until`{:class="block3control"} blocks.

--- /task ---

--- task ---
Also add the `speed`{:class="block3variables"} square block under the `when green flag clicked`{:class="block3event"} block:

```blocks3
set [speed v] to () :: variables
```
Changing the value `1` here will alter the `speed`{:class="block3variables"}. The higher the value the faster the sprites will move.

--- /task ---

## finished 
--- task ---
The `finished{`:class="block3variables"} variable acts as a switch set to `true`{:class="block3variables"} at the start of the game `when green flag clicked`{:class="block3event"}. At the end of the sequence, when the first sprite has shown its surprise costume and reverted back to its original costume, the `finished{`:class="block3variables"} variable switches to `true`{:class="block3variables"}.

Add the block  below under the speed block:

```blocks3
set [finished v] to (true) :: variables
```
--- /task ---

--- task ---
Add the following block as the very last block in `when green flag clicked`{:class="block3event"}:

```blocks3
set [finished v] to (false) :: variables
```
--- /task ---

In the next step you will use `false`{:class="block3variables"} to communicate to all the sprites next stage of the game.
