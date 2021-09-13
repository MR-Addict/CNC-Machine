Grbl is a very popoular open source firmware controlling machine running.

Standard grbl doesn't support servo control, before v1.1, grbl doesn't support laser too.
But arduino community is very powerful, many people distribute their modified grbl supporing sero and plotter,
enven some other steppers like 28BYJ-48 steppers.
I collect a version that I think is perfect for my project, that is geblServo1.1.
More information about this version, please go to https://github.com/lavolpecheprogramma/grbl-1-1h-servo

Grbl is a bridge between MCU and machine through gcode language.Thus you need a software to generate gcodes, 
and Lasergrbl is a perfect choice for us.Check it out in Software folder.