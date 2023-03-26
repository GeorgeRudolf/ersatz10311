# ersatz10311
A preprocessor/pod dongle/probe/whatever for connecting HP Logic Analyzers pod cables directly to a 68000/68010 CPU in DIP package.


Exactly what says on there. Designed for assembly at JLC, you'd be nuts to try and hand solder the 147+ passives on this thing, 5 units should cost roughly $40 to make and ship, so you can share with friends. If you're telling me the time you'd spend to solder up one of these costs less than $40, well, I'm sorry. The pick and place and BoM files for that are included with the gerbers.

 The parts specified incur about $9 in extended library part loading fees, unfortunately HP had to spec odd values to get to 100kOhm equivalent load (ah, yup, we're using 255Ohm resistors instead of 250Ohm because go try and find those reasonably in 0402). Bring your own m68k socket, shrouded 40 pin connectors and mating connectors for the target.

This project is free for personal use. If you do resell, this license requires you do so at no more than cost+postage+a small nominal fee (say, a coffee or a beer).
![image](https://user-images.githubusercontent.com/24400566/227787679-91c9d7ba-902a-4e5e-8911-dee1114ed1ff.png)
