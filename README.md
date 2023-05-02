# Control_Motor_and_LCD

Build a system using Nios II in kit DE10 to connect a LCD16x2andan H-bridge to control a motor. This system can do the following tasks:
+ When SW0 is ON, LCD blinks the sentence “Hello World !!!” in the middle of row 1 with frequency 1Hz. (Using timer)
+ When SW1 is ON, Nios II controls the motor by sending PW Mpulses to the H-bridge. LCD displays the duty cycle andthefrequency of PWM pulses. 
+ When SW0 and SW1 are OFF, turn off 
+ SW1, SW2, SW3 will control the speed of the DC motor basedonthe PWM Pulses be created by DE-10 kit nano.
