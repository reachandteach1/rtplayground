 RT Playground by Reach and Teach 2017-2019
 This code allows the Adafruit Circuit Playground to be used as a basis for 
 tinkering and inventing a wide variety of experiments without the need for programming.

 See http:www.reachandteach.com/rtplayground for ideas and documentation
 Thanks to Tony diCola for the megademo code that the mode switching is based on.
 Thanks to Carter Nelson for Capacitive tone logic

 The following programs are built into this code (in order):
 - Rainbow cycling demo - Looks pretty
 - Operation - Tone sounds when input is grounded, Lives countdown from 10, Beethovens 5th sounds at 0
   Create your own operation game with tin foil cups and chopsticks or a make an agility game.

 - Capacitive music keyboard
   Play music with flowers, feet, balloons, etc. make a music box or organ grinder.

 - Contact tag - Grounding input causes tone to sound and lights to cycle. Also toggles a digital output on #6 and drives
   an optionally attached servo on #12

 - Light tag - Light or laser causes tone to sound and lights to cycle. 
   Make your own flashlight "laser" tag, target game. Multiple units can be placed around room. Hitting the target 
   also toggles a digital output on #6 and rives an optionally attached servo on #12.

 - Light tag 2 - This light tag randomly turns leds to red for 2 seconds then turns off.
   Light must hit target within that time. Make your own flashlight "laser" tag, 
   target game. Multiple units can be placed around room.

 - College bowl - Any capacitive touch on left side causes tone to sound and light cycles blue. 
   Right side causes tone to sound and light cycles red. Must arm by pushing left button.

 - Thermometer - temperature is displayed
   in colored leds in increments of 2 degrees. 

 - Tilt Control - built-in accelerometer is used to translate into left, right, up, and down arrows
   left and right buttons also polled as A and D keys

 - MicFFT - spectral analysis display of microphone input. Outputs information to external keyboard usb. Also drives
   a servo attached to #12

 To select a program function:
 1. Set switch #21 to the right to set the function. One of the Green LEDs should be lit.
 2. Pressing the left button #4 will cause the Green LEDs to cycle with each press in a 
    counter-clockwise direction. The upper top left LED refers to function 0 and proceeds with 
    functions 1, 2, 3, 4, 5, 6, 7, 8, 9 as described above.
 3. Set #21 to the left and the Circuit Playground will start running the selected function.
 
 Cycling the power will cause program #1 to play by default. However, you can change
 this. After selecting the program function as above, you can hold down button #4
 until you hear a beep. This will change the default program to the selected function.

 Keyboard emulation has also been added so some functions to send keystrokes to a USB attached computer
 to allow easy external score board logic, etc. using Scratch or other host computer interface

 Author: Derrick Kikuchi 
 Permission to use granted under Creative Commons Attribution + ShareAlike
