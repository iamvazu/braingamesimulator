# braingamesimulator
Brain Game Simulator | NeuroSky Mindwave | Control Windows Games Using Brain Signals<br>
Demo: https://youtu.be/iC-GXePw5X4
<img src='https://github.com/vsltech/braingamesimulator/blob/master/eegamesimulator.jpg'><br>
We are trying to automate the windows games first racing games controls using attention & meditation level values that we have captured from the frontal lobe of brain using NeuroSky Mindwave Headset.<br>
# Python Direct X game controller server
<img src='https://github.com/vsltech/braingamesimulator/blob/master/cover1.jpg'>
# DirectX works with Scancodes for Direct Input
<br>
For best results install NeroSky Mindwave Apps & train your brain: https://store.neurosky.com/products/blink-zone
Check attention/meditation values using my code: https://github.com/vsltech/neuroskymindwavecapture
<br>
*Install thinkgear connector: https://store.neurosky.com/products/pc-developer-tools 
Dependencies: PyWin32, Mindwave, Python2.7, ThinkGear Connector<br>
*I used Python2.7 64-bit on Windows10 OS
<li>PyWin32: Download & Install from below links<br>
Using exe: https://sourceforge.net/projects/pywin32/files/pywin32/Build%20221/pywin32-221.win-amd64-py3.6.exe/download<br>
Using pip: http://www.lfd.uci.edu/~gohlke/pythonlibs/#pywin32
</li>
<br>
Run this program in background, once Headset led turns green you will start seeing attention, meditation & eye blink values. Don't shake headset as raw values flickers with small change on contact from frontal lobe/forehead.<br>
EDITS in the code: braingamesimulator.py<br>
*headset = mindwave.Headset(<ENTER_YOUR_COM_PORT_IN_DEVICE_MANAGER>, 'CC0E')<br>
Calibration: Edit your threshold value with your attention/meditation values
<br>
For issues read this: http://www.vslcreations.com/2017/05/neurosky-mindwave-issues-beginners-guide.html
Ref/Credits: https://github.com/BarkleyUS/mindwave-python, <a href="https://www.linkedin.com/in/utkal-sharma-b70b7265/" target="_blank">Utkal Sharma</a>
