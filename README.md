# Raid-Array-Setup-on-Server

<h2>1) Access BIOS settings</h2>
Boot the server if it is off or restart if it is already on. As the server boots press the <b>Delete</b> or <b>F2</b> key to enter into the BIOS. <b>(Warning! Depending on the age of your model, the key may be different.)</b>

<br />
<br />
Your screen should look something like this:
<br />
<br />
<p align="center">
<img src="https://imgur.com/tQ53lgM.png" height="65%" width="65%" alt="BIOS"/>
</p>

<h2>2) Enabling RAID</h2>
Step 1) On the left of the screen expand <b>System Configuration</b> by clicking on the small red "+" sign to the left of the name of the file.
<br />
<br />
Step 2) From the revealed options click directly on SATA Operation
<br />
<br />
Your screen should look something like this:
<br />
<br />
<p align="center">
<img src="https://imgur.com/mggDTJu.png" height="65%" width="65%" alt="SATA Op"/>
</p>
<br />
<br />
Step 3) As in the image above select <b>RAID On</b> in the menu on the right and select <b>Apply</b> on the bottom of the screen 

<h2>3) Configuring a RAID5(parity) array int the motherboard RAID configuration utility</h2>
Step 1) After selecting Apply in the previous step click on <b>Exit</b> located to the right of the Apply button. This will trigger the system to restart. As the system restarts the BIOS will load and then the RAID controller will automatically load.
<br />
<br />
You will be presented with a similar screen as follows:
<br />
<br />
<p align="center">
<img src="https://imgur.com/0EU6y77.png" height="65%" width="65%" alt="Raid Config"/>
</p>
<br />
<br />
Step 2) At this moment you will have limited time to press <b>Ctrl + i</b> on your keyboard and enter into Configuration Utility.
<br />
<br />
Your screen should look as follows once <b>Ctrl + i</b> has been pressed:
<br />
<br />
<p align="center">
<img src="https://imgur.com/2pz0w11.png" height="65%" width="65%" alt="Raid Config"/>
</p>
<br />
<br />
Step 3) As in the image above with <b>Create RAID Volume</b> selected, press Enter on your keyboard.
<br />
<br />
You should be presented with the following image:
<br />
<br />
<p align="center">
<img src="https://imgur.com/IcVcxxy.png" height="65%" width="65%" alt="Raid Config"/>
</p>
<br />
<br />
Step 4) To navigate through the available options use the <b>Tab</b> key on your keyboard. To return to the top of the Option list keep pressing tab until you are at your desired line.<br />
Feel free to name your RAID array as desired.<br />
Move down to <b>RAID Level</b> with <b>Tab</b>. Using the <b>Up</b> and <b>down</b> keys on your keyboard select the disired RAID array configuration. In this tutorial we will select <b>RAID5 (Parity)</b>
<br />
<br />
Step 5) Move down to <b>Disks</b> and with <b>Select Disks</b> highlighted press <b>Enter</b> on your keyboard.
<br />
<br />
Your screen will look as follows :
<br />
<br />
<p align="center">
<img src="https://imgur.com/lDmGqRi.png" height="65%" width="65%" alt="Raid Config"/>
</p>
<br />
<br />
Using the <b>Up</b> and <b>Down</b> keys on your keyboard to navigate, select the desired disks you would like to include in your RAID array by pressing the <b>Spacebar</b>. <b>(Please not that a minimum of 3 disks are required for a RAID5 configuration)</b>
<br />
<br />
A green triangle should appear by the selected disks as follows:
<br />
<br />
<p align="center">
<img src="https://imgur.com/on9Q93D.png" height="65%" width="65%" alt="Raid Config"/>
</p>
<br />
<br />
Step 6) Press <b>Enter</b> when all desired disks have been selected.
<br />
<br />
Step 7) Press <b>Tab</b> to move to <b>Strip Size</b>. As recommended underneath on your screen select <b>64KB</b> as the typical value for RAID5 using your <b>Up</b> and <b>Down</b> keys.
<br />
<br />
Step 8) Keep <b>Capacity</b> at the default value.
<br />
<br />
Step 9) With <b>Create Volume</b> highlighted press <b>Enter</b> on your keyboard to create the Volume.
<br />
<br />
Step 10) A warning message will appear indicating that data on selected disks will be lost. This is why you should not select a disk containing the Operating System files unless absolutely intentional. Press <b>Y</b> to confirm the volume creation.
<br />
<br />
Step11) Press the <b>Esc</b> key on your keyboard followed by <b>Y</b> to confirm to exit the configuration utilty and restart your computer.
