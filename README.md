Automatic Bed Mesh with BLTouch/Probe Offset

## Install 

1. Add the following to the top of printer.cfg: 
<pre>[include bed_mesh.cfg]

[gcode_macro printer_settings]
variable_print_area_x: 350
variable_print_area_y: 350

gcode:
</pre>

2. Edit print_area_x and print_area_y with the maximum printable area of your printer.

3. Download bed_mesh.cfg and upload it to the same folder as printer.cfg through Fluidd/Mainsail.
