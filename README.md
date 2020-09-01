# MultiMicrophone-Speaker-Localization-Demo-System

This projects goal is to localize a speaker inside a room using a microphones array.
The code is written in Matlab and is ran from a Matlab GUI.

![Blocks_diagram](/Blocks_diagram.PNG)

**Code Structure:**
* GUIAA.m - run this file to open the GUI and start the run
* data_aquisition.m - functions for sound signal acquisition from each microphone
* detection_unit.m - detection of speaking periods
* SNR_Finder.m - detects speaking periods and silent periods and derives the SNR
* ZeroCrossing.m - functions that helps detecting speaking periods
* Signal_Processing.m - noise cleaning functions and peak detection functions
* plotting.m - function for the plotting process of the results
* BP_Chooser.m - function that helps the signal processing by choosing the band pass filter to be applied
* mic_reduction.m - functions that ingore microphones that recieved low quality signal
* new_filters\ - directory containing band pass filters for the BP_chooser functions

This project was done under supervision of SIPL lab at The Technion - Israel Institute of Technonology 

![SIPL_logo](/SIPL_logo.png)
