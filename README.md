# SignalTargets

These are typical North American  signal targets.  Included is a FreeCAD macro
file  (Python  code)  to  create  the 3D  printable  heads,  as  well  as PCBs
containing   SMD  LEDs  to  light  the  signals.  Not  included  are  mounting
materials: masts for single signals or bridges for groups of signals.

Files:

-  5x5_panel.json  5 by 5 panel  spec.  used as input to KiKit to  create  the
panelized PCBs.
- OneLampR_5x5_Panel.kicad_pcb 5x5 panel of single lamp (Red) signal heads
- ThreeLamp_5x5_Panel.kicad_pcb 5x5 panel of three  lamp  (Green-Yellow-Red)
signal heads
- TwoLampGR_5x5_Panel.kicad_pcb 5x5 panel of two lamp (Green-Red) signal heads
- TwoLampYR_5x5_Panel.kicad_pcb  5x5  panel of two lamp  (Yellow-Red)  signal
heads
- SignalTargets.FCMacro  FreeCAD macro (Python code) to generate STL files of
the signal targets.
- SignalTargets/SignalTargets.kicad_pro KiCAD "source" for the PCBs.
