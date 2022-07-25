# Traffic light controller using Arduino
The code for this traffic light controller is simple and easy to understand. We have exhibited traffic lights for a three-way road. The LEDs will be glowing in a particular sequence to form an actual traffic light controller system.

At a time, two red LEDs will glow, and one Green LED will be ON. Also, two yellow LEDs will be ON for one second. Yellow LED will Glow on each transition between RED to GREEN. In short first RED LED will glow for 5 Seconds, then YELLOW for 1 second, and then Green LED will ON for 5 seconds.

In the void setup of the code, we have defined the pins for the LEDs as outputs from 2 to 10. In the void loop section, we have defined the functions to turn LEDs ON and OFF into the sequence.
