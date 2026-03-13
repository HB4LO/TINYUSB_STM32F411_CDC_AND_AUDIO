# First, we have to create the CubeMX project & configure peripherals
<p align="left">
  <img src="images/1.png" width="800" title="Search for Microcontroller">
</p>

<p align="left">
  <img src="images/2.png" width="800" title="Activate Oscillators">
</p>

<p align="left">
  <img src="images/3.png" width="800" title="Activate SWD">
</p>

<p align="left">
  <img src="images/4.png" width="800" title="Activate USB">
</p>

<p align="left">
  <img src="images/5.png" width="800" title="Enable Interrupt">
</p>

<p align="left">
  <img src="images/6.png" width="800" title="Configure Clock">
</p>

<p align="left">
  <img src="images/7.png" width="800" title="Generate Code">
</p>

# Then, we configure the Cude IDE environments + Add some lines of code
<p align="left">
  <img src="images/8.png" width="800" title="Create/Import">
</p>

<p align="left">
  <img src="images/9.png" width="800" title="Select Directory">
</p>

<p align="left">
  <img src="images/10.png" width="800" title="Import Project to IDE">
</p>

Download the github project and Copy past the files to your project 

<p align="left">
  <img src="images/11.png" width="800" title="Importing tinyusb">
</p>

<p align="left">
  <img src="images/12.png" width="800" title="Copying Inc files">
</p>

<p align="left">
  <img src="images/13.png" width="800" title="Copying Src files">
</p>

<p align="left">
  <img src="images/14.png" width="800" title="Adding Tinyusb Source Codes">
</p>

<p align="left">
  <img src="images/15.png" width="800" title="Adding Tinyusb Source Codes 2">
</p>

<p align="left">
  <img src="images/16.png" width="800" title="Adding Tinyusb Source Codes 3">
</p>

<p align="left">
  <img src="images/17.png" width="800" title="Adding Tinyusb Src to path">
</p>
<p align="left">
  <img src="images/18.png" width="800" title="Adding Tinyusb Src to path 2">
</p>

<p align="left">
  <img src="images/19.png" width="800" title="Adding Tinyusb Device to path">
</p>

<p align="left">
  <img src="images/20.png" width="800" title="Adding Tinyusb Device to path 2">
</p>

<p align="left">
  <img src="images/21.png" width="800" title="Verifying the Includes">
</p>

<p align="left">
  <img src="images/22.png" width="800" title="Adding to main.c">
</p>

<p align="left">
  <img src="images/23.png" width="800" title="Adding to main.c 2">
</p>

<p align="left">
  <img src="images/24.png" width="800" title="Adding to stm32f4xx_it.c">
</p>

<p align="left">
  <img src="images/25.png" width="800" title="Adding to stm32f4xx_it.c 2">
</p>

<p align="left">
  <img src="images/26.png" width="800" title="Build all 1">
</p>

<p align="left">
  <img src="images/27.png" width="800" title="Build all 2">
</p>

<p align="left">
  <img src="images/28.png" width="800" title="Programm">
</p>

# Let's test That, plug the USB C (Audacity must be installed)! 

<p align="left">
  <img src="images/usb.png" width="800" title="this is fine">
</p>

<p align="left">
  <img src="images/29.png" width="800" title="Device manager shows USB headset & COM PORT">
</p>

Select "Tinyusb headset" as the Output audio device. 

<p align="left">
  <img src="images/30.png" width="800" title="Selecting Audio output">
</p>

Open audacity and set Input = Tinyusb, output = headset or speaker (depends on your PC) 

<p align="left">
  <img src="images/31.png" width="800" title="Configure inputs/outputs">
</p>

<p align="left">
  <img src="images/32.png" width="800" title="Configure inputs/outputs 2 ">
</p>

Choose your favourite music, for example : https://www.youtube.com/watch?v=dQw4w9WgXcQ
Start recording with Audacity
<p align="left">
  <img src="images/33.png" width="800" title="Recording audio loopback">
</p>

Play back what you just recorded (You now have a loopback working) ! 
Let's try with a 500Hz Low pass filter 

<p align="left">
  <img src="images/34.png" width="800" title="Activating the Audio Filter">
</p>

# CDC testing (Putty is required, or equivalent) 
Open the COM port that just has been created. Whatever you type is shown back
<p align="left">
  <img src="images/35.png" width="800" title="Openning COM PORT">
</p>

<p align="left">
  <img src="images/36.png" width="800" title="Enjoy COM PORT LOOPBACK">
</p>