# CMPE453 Embedded Systems

## Lab 2 - Traffic Light With Counter

> [!NOTE]
> [AVR Programming Library](https://github.com/hexagon5un/AVR-Programming/tree/master/AVR-Programming-Library) must be 
downloaded and added to the Arduino IDE to compile the code. The library can be added by going to 
Sketch -> Include Library -> Add .ZIP Library and select the downloaded library.

1.  Set up the following circuit with your breadboard, Arduino-Uno, 7-segment
display, 220Ω resistors (11), 3 LEDs and jumpers.

![Figure 1 - Circuit](https://github.com/elifnazlib/CMPE453-Lab2-TrafficLightWithCounter/blob/main/circuit.png)

2. Program the microcontroller by using C programming on Arduino IDE.
Provide	the	connection between your computer and Arduino board. When
your program runs, it should follow the following cycle:

    1. 7-segment display will start from 9 and count down to 0 and like real clock.
From beginning 9, up to	counter	becomes	5, only Red	LED	should be ON.
When counter is 5, Red and Yellow LEDs both should be ON. When the
counter	becomes	0, Red and Yellow LEDs should be OFF and Green LED
should be ON. The counter should be set to 7 at the time of Green LED is ON
and wait 7 seconds while 7 is visible on the 7-segment display.
    2. The counter should count from 8	down to	0.	When it	becomes	4, Green LED
should be OFF and Yellow LED should	be ON. When	counter	becomes	0,	Red
LED should be ON and others should be OFF. Then, Program should return
to A.
  
> [!NOTE]
> [This documentation](https://docs.arduino.cc/retired/hacking/software/PortManipulation/) has been used to understand which ports correspond to which pins on the Arduino Uno board when programming with C.
