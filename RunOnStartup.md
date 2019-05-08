Recommended: Method 2: .bashrc
<br />This method to run a program on your Raspberry Pi at startup is to modify the .bashrc  file. With the .bashrc method, your python program will run on boot and also every time when a new terminal is opened.

<br />In terminal type the following command:
<br />sudo nano /home/pi/.bashrc

<br />Go to the last line of the script (below "fi") and add the following lines:
<br />xhost +
<br />echo Running at boot 
<br />sudo python /home/pi/sample.py
