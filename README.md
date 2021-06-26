# Controling-DC-motor-with-L293D
This is REAADME for Controling DC motor with L293D driver
## Components 
* Board
* Arduino uno
* 2 DC motor
* L293D driver
## Precedure
* first we need an external battery (7-20) V to run the motors ( arduino doesn't have the capacity for it )
* Connect Pin Enabler (pin 1 of driver) to arduino's pin 5 (must be pwm pin) to control the speed
* plug Pins 2&7 to arduino's pins 3&4 respectfully to control the direction 
* Pins 4&5 to the ground 
* finally connect Pins 3&6 to the motor 
* repeat the same steps for the second motor
## Codes Notes 
* we choose the speed by defining analog pin No. 5 
* we can choose the direction clockwise/anticlockwise by changing LOW/HiGH in OUTPUT 3&4
* you need to set the speed at 100 at least to kick off

