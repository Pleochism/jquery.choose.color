Notes to self.

TODO:

• Try creating the colour wheel with three (r, g, b) overlapping radial gradients, just to see quoi ça nous donne.

• DONE The chooser canvas ought to go in a position parent div, so that coordinates for the point can be the same as the canvas.

• DONE The colour wheel could be cached as image data so we don't have to re-render on each slider move. Lightness could then be simulated with a colour underneath.

• DONE Opacity values are unreliable. Either find out why in the canvas, or use CSS opacity on the canvas elem (which would also avoid re-renders of the colour wheel).