# First, we have to create the CubeMX project & configure peripherals
<p align="left">
  <img src="images/1.png"  title="Search for Microcontroller">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/2.png"  title="Activate Oscillators">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/3.png"  title="Activate SWD">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/4.png"  title="Activate USB">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/5.png"  title="Enable Interrupt">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/6.png"  title="Configure Clock">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/7.png"  title="Generate Code">
</p>
<br>
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
<br>

# Then, we configure the Cude IDE environments + Add some lines of code
<p align="left">
  <img src="images/8.png"  title="Create/Import">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/9.png"  title="Select Directory">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/10.png"  title="Import Project to IDE">
</p>
<br>
----------------------------------------------------------------------------------
<br>
Download the github project and Copy past the files to your project 

<p align="left">
  <img src="images/11.png"  title="Importing tinyusb">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/12.png"  title="Copying Inc files">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/13.png"  title="Copying Src files">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/14.png"  title="Adding Tinyusb Source Codes">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/15.png"  title="Adding Tinyusb Source Codes 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/16.png"  title="Adding Tinyusb Source Codes 3">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/17.png"  title="Adding Tinyusb Src to path">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/18.png"  title="Adding Tinyusb Src to path 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/19.png"  title="Adding Tinyusb Device to path">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/20.png"  title="Adding Tinyusb Device to path 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/21.png"  title="Verifying the Includes">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/22.png"  title="Adding to main.c">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/23.png"  title="Adding to main.c 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/24.png"  title="Adding to stm32f4xx_it.c">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/25.png"  title="Adding to stm32f4xx_it.c 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/26.png"  title="Build all 1">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/27.png"  title="Build all 2">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/28.png"  title="Programm">
</p>
<br>
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
<br>
# Let's test That, plug the USB C (Audacity must be installed)! 

<p align="left">
  <img src="images/usb.png"  title="this is fine">
</p>
<br>
----------------------------------------------------------------------------------
<br>
<p align="left">
  <img src="images/29.png"  title="Device manager shows USB headset & COM PORT">
</p>
<br>
----------------------------------------------------------------------------------
<br>
Select "Tinyusb headset" as the Output audio device. 

<p align="left">
  <img src="images/30.png"  title="Selecting Audio output">
</p>
<br>
----------------------------------------------------------------------------------
<br>
Open audacity and set Input = Tinyusb, output = headset or speaker (depends on your PC) 

<p align="left">
  <img src="images/31.png"  title="Configure inputs/outputs">
</p>

<p align="left">
  <img src="images/32.png"  title="Configure inputs/outputs 2 ">
</p>
<br>
----------------------------------------------------------------------------------
<br>
Choose your favourite music, for example : https://www.youtube.com/watch?v=dQw4w9WgXcQ
Start recording with Audacity
<p align="left">
  <img src="images/33.png"  title="Recording audio loopback">
</p>
<br>
----------------------------------------------------------------------------------
<br>
Play back what you just recorded (You now have a loopback working) ! 
Let's try with a 500Hz Low pass filter 

<p align="left">
  <img src="images/34.png"  title="Activating the Audio Filter">
</p>
<br>
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
<br>
# CDC testing (Putty is required, or equivalent) 
Open the COM port that just has been created. Whatever you type is shown back
<p align="left">
  <img src="images/35.png"  title="Openning COM PORT">
</p>

<p align="left">
  <img src="images/36.png"  title="Enjoy COM PORT LOOPBACK">
</p>