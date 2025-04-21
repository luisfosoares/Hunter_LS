# Hunter_LS
PCB implementation for Hunter Xcore irrigation system.

# Background 
Hunter XCORE is a  "dumb" system that can be locally programmed but no iOT connection is provided by Hunter. 
Solutions li like (https://github.com/marek-polak/hunter-wifi) can be implemented in homeassistant but lack active status feedback of the valves, without it ins uncertain if system was effectivelly started or not.

# Somebody worked on it already ...  
A great job was done by CZSmith at (https://github.com/czsmith/HunterMonitor) laying down the schematics for a working PCB but hardware was not available so i was up for the challange.

# The challange 
The oportunity was taken to develop a PCB.
Idea was a seamless integration into the Hunter XCORE. 

# PCB 
PCB was designed to fit the case, wave possibility to be integrated without any modification of the system. 
Design follows the schematic from CZSmith.
Through hole was the way to go, spece was not a problem and idea was to learn, solder and integrate all at home.
PCB supplied by JLC PCB.

# Software 
Managed through ESPHome as per (https://github.com/czsmith/HunterMonitor).

# Possible improvements
V1.0 comes with some "issues"
  1) Power labels and comments should been done in brighter color, not easy to read.
  2) Mistake on footprint definition of 2W10 - currently 90º rotated part vs graphic description.
  3) Hole for antena in left side of PCB its useless as antena wiring would not fit the case - Idea not practical.
  4) Rearragne components if possible to allow space for full usb cable to fit - currently only short cable/angled cable is possible.


# Interest from others 
If you are interested in this kind of item please contact me on (filipee8.net@gmail.com).

# Thanks
Thanks to CZSmith for the Schematic.

Pictures of PCB and installation.
