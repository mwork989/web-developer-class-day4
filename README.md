
CSS units can be broadly categorized into following

Absolute Units:
---------------------
px (pixels)      - 1px = 1/96th of 1in  -use this measurement when one needs to be precise and consistent across different devices and screens. commonly used 
    1.defining the size of elements e.g. height width of HTML elements
    2.spacing between two elements 

in (inches)      - 1in = 2.54cm = 96px
cm (centimeters) - 1cm = 37.8px = 25.2/64in
mm (millimeters) - 1mm = 1/10th of 1cm
    Thse units are commonly used in print media 


pt (points)      - 1pt = 1/72nd of 1in
pc (picas)       - 	1pc = 1/6th of 1in
 Thse units are commonly used when importance is given typography text and print media will adjsut the setting while printing based on this

Relative Units:
--------------------
em (relative to the font-size of the element) - used based on font 
ex (relative to the x-height of the font)
ch (relative to the width of the "0" character)
rem (relative to the font-size of the root element) - used based on font 
vw (relative to 1% of the viewport width)  - during targetting the small to medium devices
vh (relative to 1% of the viewport height) - during targetting the small to medium devices
vmin (relative to 1% of the viewport's smaller dimension)
vmax (relative to 1% of the viewport's larger dimension)
% (percentage, relative to the parent element or the viewport) - most commonly used
responsiveness 



Viewport-percentage Units: used inn mobile as well medium screen devices dimensioning 
------------------------
vw (viewport width)
vh (viewport height)
vmin (viewport minimum dimension)
vmax (viewport maximum dimension)


Angle Units: used in animation and css transitions
----------------
deg (degrees)
rad (radians)
grad (gradients)
turn (a full turn)

Duration Units:used in animation and css transitions
----------------------
s (seconds)
ms (milliseconds)

Frequency Units: Use for defining audio or video frequencies.
--------------------
Hz (hertz)
kHz (kilohertz)

Resolution Units: defining the resolution of screens and images.
-------------
dpi (dots per inch)
dpcm (dots per centimeter)
dppx (dots per pixel)
