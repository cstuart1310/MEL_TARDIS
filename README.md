# MEL_TARDIS
Just a script in MEL that makes a model fade in opacity and randomly adjust position

This script reacts based on the current level of a sine wave that it follows. At the peak of the wave, the TARDIS remains visible and still. As the wave decreases, so does the model's transparancy (Using the opacity and transmission shader values within Arnold). When the model is completely invisible within the scene, a random position is chosen which it is placed at, causing the effect of it teleporting smoothly.

In order to use it, you must first assign an AiStandardSurface material to your TARDIS model. You then just need to replace "mat_tardis.transmission" with your material name and "tardis" with the name of your object.

The Min and Max values refer to the maximum distance that the TARDIS can travel in any axis, and adjusting the amount that the cosVal is divided by changes the speed of the effect.
