# MEL_TARDIS
Just a script in MEL that makes a model fade in opacity and randomly adjust position

This script reacts based on the current level of a sine wave that it follows. At the peak of the wave, the TARDIS remains visible and still. As the wave decreases, so does the model's transparancy (Using the opacity and transmission shader values within Arnold). When the model is completely invisible within the scene, a random position is chosen which it is placed at, causing the effect of it teleporting smoothly.
