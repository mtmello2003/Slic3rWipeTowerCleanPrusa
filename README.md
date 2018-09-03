# Slic3r Wipe Tower Cleanup - Prusa Edition
Cleanup the wipe tower gcode generated from Slic3r Prusa Edition and add your own tool change code.
(if you are not a owner of an Original Prusa printer and want to use slic3r wipe tower...) 

Tested with Slic3r PE 1.41.0 beta + python 2.7

TO DO:
- Get tool change gcode from Slic3r insted of fixed in the script.

PS:
- This script needs to run at the same path of saved .gcode file; otherwise slic3r show script permission error (bug?!)
- Set Filament Settings > Advanced > Ramming setting > total ramming time = 0
