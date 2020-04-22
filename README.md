# Mic Level Locker
Simple little script that forces the mic audio level to stay the same. I needed this due to Microsoft Teams Stuffing up my audio. 

This script was adapted to work on Windows 10. The orignal floats around on the internet somewhere and was designed for Windows 7, and does not work properly on Windows 10.

This is configured to set the volume to 50%. If you wish to use a different value, go into lock_mic_vol.bat and change `32768` to another value. (65536 is 100%).

To use the script, launch `LockMic.bat`. The script runs in the background and will not be noticable to you. If you want to see if it's working, try to change the input volume of your mic. 
