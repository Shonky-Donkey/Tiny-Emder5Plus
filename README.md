
# Tiny-Emder5Plus
Core-XY topper for an ender 5+ built from the Tiny-M (V4) https://github.com/gsl12/Tiny-M 
![Tiny-Emder5_1](https://user-images.githubusercontent.com/88253304/128261054-d3563549-79d8-4654-bcef-58df6ae0884f.png)

The Y axis is flipped, but the printed plastics have not changed from the Tiny-M. 

Different bits required from the Tiny-M:
* Longer bolts (2 of the M5 x 25 and 4 of the M5x40 will need to be M5x60. 2 of the M5x40mm are because they now also have to pass through some of the 2020 extrusion to go into the end of the 2020 below. I might design some jigs to aid in drilling these holes. The other 4 bolts are to go into a new brace for the motor mount.
* longer pulleys... who knows how long?
* extra braces for motor mounts (Will upload CAD when I design them)
* Some extra hardware for the braces. May be able to steal this from the ender 5.
* will need two identical motors for AB motors. The ender X and Y motors are diferent, so you could try and sorce a single one of either. I'm personally probably just going to buy two matched motors. Probably whatever is used on the Voron 2
* 2020 extrusion (with the 4-4.2mm holes as described in Tiny-M docs) - 2x 561mm and 1x498mm (to be confirmed if the CAD I have for the Ender is accurate)
* MGN9 rail - 2x500mm(445mm if mounted on the lower extrusion) and 1x 438mm


Bit not required from the Tiny-M:
* Z axis
* much of the extrusions
* some of the hardware

You are on your own for now with the extruder/hot end mount. Not sure what I am going to do yet. Maybe put the OEM Ender on for now. Will need to design or find CAD for that. ultimately might put an orbiter, Biqu H2, or Mellow NF-sunrise on. I'm hoping it will ultimately need a Volcano hot end, or I might be wasting my time here.


I'm going to build mine with the stock Ender 5 plus board and Raspberry Pi running Klipper. In theory you should be able to run almost any main board (BTT etc) with klipper, but if you do, you are own your own. Who knows if I can even figure out the config for myself... 


![Tiny-Emder5_2](https://user-images.githubusercontent.com/88253304/128361120-4be30d8a-43f2-4d9f-8159-d41705b5a592.png)
The linear rails could be mounted either on the top rail, with the X axis carriage flipped, or on the bottom rail, with the carriage running as it does on the tiny-m. HOWEVER... if it is mounted with the rails on the lower extrusions, the inner extrusions for the Z axis will need to be machined down. I've shown in the image below where it will foul. Having it in this configuration should result in a stiffer overall design though, as there is much more ridigity with the essentially 3x2020 profiles in an L shape here.
![Tiny-Emder5_3](https://user-images.githubusercontent.com/88253304/128361130-9e390330-764f-4885-954e-613fd8093db2.png)

Untested, and unfinished.

Ender 5 CAD shamelessly mooched from https://grabcad.com/library/creality-ender-5-plus-1

-Shonky.
