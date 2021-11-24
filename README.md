Add the following to the top of printer.cfg:

<pre>[include bed_mesh.cfg]

[gcode_macro printer_settings]
variable_print_area_x: 350 ; maximum printable area
variable_print_area_y: 350 ; maximum printable area
</pre>

Download bed_mesh.cfg and upload it to the same folder as printer.cfg
