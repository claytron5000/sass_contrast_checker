# sass_contrast_checker
Probably an unneeded tool to check the contrast ratio of the foreground to the background using the w3c definitions of luminence and contrast. I may have the math wrong, though I tried to follow their numbers in http://www.w3.org/TR/2008/REC-WCAG20-20081211/#relativeluminancedef. Assumption is sRGB.

The next step is to make a mixin, However, this has limited utility since it only compares the foreground and background of one set of colors, hence a single element. 

A tool that actually crawls the DOM in a would be a better auditor.
