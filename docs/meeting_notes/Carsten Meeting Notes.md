# Meeting Notes With Carsten
## <2026-2-19> Notes from meeting with Carsten Re: Salp PCB
## Some Todo Items:
- [x] find old tutorial that shows making custom fat solder pads (Brian) see Phil's Lab video below
- [ ] add the ~1 in by ~2 in (check notes for exact dimensions) PCB edge to the board layout
- [ ] drag, flip, rotate, etc to minimize signal crossings
- [ ] Route 20 mil for signal traces 
- [ ] Route 40 mil for power traces (Anything connecting the battery)
- [ ] either edit board footprint or change part to match jst-sh 6 pin connectors we have in the lab
- [ ] loop back and check on the via's under the board for the battery connections

## Notes on trace width:
- for calculating minimum trace width that is a function of copper thickness, allowable temperature rise, acceptable power loss, etc

- Note that the acceptable power loss appears to be the limiting factor more than allowable temperature rise in this case.

## Some useful Websites:
- For Design tolerances
https://jlcpcb.com/blog/how-to-avoid-pitfalls-in-pcb-design

- calculating pcb minimum trace widths
https://www.newark.com/pcb-trace-width

- The Xiao Seeed Wiki (info on the microcontroller)
https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/

- for understanding board to board solders with castellated edges such as our esp32
https://learn.sparkfun.com/tutorials/how-to-solder-castellated-mounting-holes/all


* This tutorial shows creation of a carrier board (i guess this is the right name for the board we are designing. Starting from 06:15 in the video Phil shows how to create the solder pads that match his castellated board. This method should match exactly what we have to do.
https://www.fedevel.com/blog/kicad-rp2040-module-carrier-board-design-phils-lab-29
