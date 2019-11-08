# Installation
## Python
The python code relies on the "sounddevice" package. Install this using:
'''pip install sounddevice"
## MATLAB
The MATLAB code relies on the Audio Systems Toolbox. To install it go to the add-on manager in MATLAB IDE,
search for this toolbox and install it. This is not a standard toolbox so you may need to check with your
insitution to make sure you have access to it (I had to get Brown to purchase it). If you cannot get access 
the Python code works just as well.
# Description of files
## NeuroDAC_MATLAB_Sine.m
This is a script to play 30 seconds of a sine wave a different frequencies on each channel.
This is helpful for testing the system and making sure that you have all the software installed properly.
## NeuroDAC_MATLAB_Stream.m
This is designed to stream pre-recorded data out through the device. It has been written for Blackrock NS5 files
and scales the output values according to that. You will need to modify the scaling values for your system.
## NeuroDAC_Python_Sine.py
This is a Python file that works similarly to the MATLAB_Sine script described above. Use this to test your system.
# Coming Soon
I am still working on a full API to communicate with the device but for now please see these example scripts for an idea 
of how to communicate with the device.