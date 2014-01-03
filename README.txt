CmdPromptCmdTest App
====================

This application is just a test app to see how to initiate, control and get output of Command Line scripts/Apps from within a C# app.

We need this functionality in the Ejaaduino App and so, most of the code used there will be tested here for making a GUI (specific to Ejaaduino) which uses avrdude at the backend...

Maybe this will be somewhat helpful for some beginner like us.

The Code is NOT the msot efficient or the clean one, but emphasis is on getting it to WORK first.


CHANGE LOG
==========

v1.0 (INITIAL COMMIT)
---------------------
basic barebones functionality implemented.
* calls avrdude
* gets output/error of avrdude back in the form
* single class hence code is hacked to work, uses a timer and global var and the like