# Cyloidal-Reducer

CAD files for a 12:1 cycloidal reducer.           
BOM for CAD files:
Filament: I printed in PLA and had no major problems.
Stepper: I used a NEMA 17.
Bearings: Generic 0.625" OD 0.125" ID bearings.

Ok time for advice and know issues. First of all I'm don't fully recommend just using my designs, if possible design your own with some of my reccomendations.
All issues/tips starting from the bottom of the design:
The clearance between the bolt holes and the supports for the outer pin ring is not enough, the supports shoud be further from that hole to allow the bolt to fit properly. I was able to make it work, but it wasn't optimal.
Secondly, the outer ring and its supports are poorly designed for 3d printing, they required a huge ammount of support to print, you can probably design a more efficient way to support the pins. If you don't do that, it's slightly more efficient to print upside down (with the top of the pins on the print bed).
Next, the hole for the motor shaft on the primary input shaft was too small. I fixed this by scaling up the printing size in the slicer (worked out ok for me due to designing some wiggle room) but you may wan to change that.
Moving on the posts used to contain the bearings on the primary bearing assembly were a bit too small. I fixed this by just super gluing them into place. This wasn;t an issue on the uppermost bearing due to the input shaft being scaled up.
Second to last, the central cycloidal gear is too large when printed at 100% scale. I printed at 98.5% but you might be able to get away with less. Try to decrease it's size as little as possible as it leads to increased backlash.
Finally, the pins on the output shaft were slightly too large, leading to too much friction. I had to reprint with a smaller size (the change is in the CAD files so you should be fine, just be weary of this if you are designing from scratch).

Here is the link to the feature script I used:https://forum.onshape.com/discussion/7567/cycloidal-gear-generator
Once everything is printed I recommend liberally greasing with vaseline/

Good luck! Please message me with any questions that you have. 
