# Javascript-Raytracer
It's pretty.

To use it, just download the files and click on the Raytracer.

It might require a good graphics card to play at a decent framerate/good resolutions; to tweak the resolution, ctrl-F (find) and replace the values for pixelsX and pixelsY with any other number. Make sure to update the canvas size at the top of the file to match.


Issues:
-Screenspace distortion artifacts when pitching up or down drastically. Everything gets stretched out and flat like a pancake below and above the screen. This is from the code that determines where to place each ray at the start; there should not have to be major changes to the raycasting algorithm itself in order to amend this. I just have to figure out the vector math, which is hard to look up.

Plans:
-Utilize Bresenham's algorithm; this should hopefully bring performance gains. I've unsuccessfully tried to implement this in the past multiple times. 
