# Arduino_Steering
Cheap DIY Steering Wheel using Arduino 

>> Abstract:
   This project was made because I am a gaming enthusiast and I couldn't find cheap alternatives for a gaming steering wheel. So, I
   figured, with some DIY spririt, let's just make. I used Arduino Uno as it was just lying around. This project is a compilation of
   free softwares already available on the internet with a few changes of my own.
  
>> Background:
   The Arduino Uno in its normal operation has the potential to bilaterally communicate but it doesn't. Hence we have to change that. 
   We can do that by uploading a ".hex" file into the Atmega microcontroller ROM. This will enable the microcontroller to work
   bilaterraly and act as a controller.
   
>> Downloads:
   We require the following tools and softwares to make the arduino act as a GamePad:
   1. Atmel Flip: To upload .hex to the microcontroller.
      Link: http://www.atmel.com/tools/flip.aspx
   2. UnoJoy: To instantly convert the Arduino into a Joystck or a normal one.
      Link: https://github.com/AlanChatham/UnoJoy/tree/master/UnoJoy
   3. XOutput: Some games use only Xinput format, so this is used to convert a generic controller to a Xbox xinput.
      Link: https://github.com/Stents-/XOutput
   4. SlimDX: Used for operation of XOutput.
      Link: https://slimdx.org/index.php      //Download the version compatible with your OS. 
