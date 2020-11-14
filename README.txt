'Perspect' perspectiion correction utility

what does this program do?
- display the image file given in cli argument in a window
- let you select 4 coordinates with left mouse button
- you can move an already pinned point by clicking again so then the closes point will be moved over
- remove a pin point by right-clicking nearby
- middle-click redraws the helper quadrangle

KEYS

F1 - perspective correction (distort) and crop, then open resulting image
F2 - crop around on bounding box, then open
F3 - rotate the image so the drawn line segment (pin 2 points down only, not 4) to be horizontal
F4 - rotate the image so the drawn line segment (pin 2 points down only, not 4) to be vertical
Ctrl-S - save as dialog
Ctrl-O - open in gPicView
ESC - close

HINTS

images are not scaled, but displayed at the original size, so
a window manager which supports Alt-dragging and window regions being out of the screen
is recommended to work on large images.

REQUIREMENTS

- gtk-2, pygtk
- imagemagick, convert(1) is called internally
