LUMI is a fun midi keyboard which can light up its keys with different colors.

This project is an effort to drive those lights without using the ROLI-provided software.
It is based on reverse engineering the sysex commands that are used by ROLI Dashboard to communicate with LUMI.

The SYSEX API is described in SYSEX.txt

The default littlefoot program that is run on the LUMI is in "LUMI Keys Block Default Program.littlefoot"
It is distributed in the resources of ROLI Dashboard.

There is a `lumi_sysex.js` library which contains a few functions to control basic behaviour of the keyboard
and an example index.html file which showcases how to use the library.

The demo can be tried at https://benob.github.io/LUMI-lights/. It requires that your LUMI is identified as device 37 and that it is the second midi device on the host (the default on linux). 
