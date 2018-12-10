# stuntcarremake

[![stuntcarremake Linux build status](https://travis-ci.org/ptitSeb/stuntcarremake.svg?branch=master)](https://travis-ci.org/ptitSeb/stuntcarremake "stuntcarremake Linux build status") [![stuntcarremake Windows build status](https://ci.appveyor.com/api/projects/status/3b9bd69a4vsy0eu6/branch/master?svg=true)](https://ci.appveyor.com/project/ptitSeb/stuntcarremake/branch/master "stuntcarremake Windows Build status")

This is a port to Linux & OpenPandora of Stunt Car Racer Remake, a windows remake of the old Stunt Car Racer from the AtariST/Amiga time.

To build on Linux, simply use `make LINUX=1`
For ODroid it will be `make ODROID=1`
and for PocketCHIP: `make CHIP=1`
a simple `make` will build for Pandora.
Also, you can also use SDL2 instead of SDL1, by adding `SDL=2` to the make command (so SDL2 Linux is `make LINUX=1 SDL=2`)

Some code (the OpenAL part) come from Forsaken/ProjectX port by chino.

Controls are:
On Linux / Windows
 4 Arrows for Turning / Accelerate / Brake
 Space for Boost

On Pandora
 DPad Left/Right for turning
 (X) Accelerate
 (B) Brake
 (R) Boost

[![Play on Youtube](https://img.youtube.com/vi/qKTFntQtG6E/0.jpg)](https://www.youtube.com/watch?v=qKTFntQtG6E)

Here is a video on StuntCarRemake running on the OpenPandora

Original project is here: http://sourceforge.net/projects/stuntcarremake/
