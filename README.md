
SmokingWeener v0.2 by Raymond Spangle (https://github.com/lleevveell66)
-----------------------------------------------------------------------
This python script is meant to help ween me off of cigarettes.  It will eventually "learn" my current habits, and begin to adjust to me.  I am sharing it, because it could eventually also help others with their habits.

For now, it's running on a Raspberry Pi Zero WH with: 
- Velleman Active Buzzer Module (VMA319) on pins 9 (GND) and 11 (GPIO 17)
- NTE Electronics SPST Round Panel Mount Push Button (54-700-B) on pins 12 (GPIO 18) and 14 (GND).  

Note that the Buzzer module middle pin is not used.  GND goes to the pin labeled "-" and GPIO 17 goes to the pin
labeled "S".
 
 Active
 Buzzer
 Module    RPzWH
.------.  .------.
|  (O) |  | 1  2 |
|S    -|  | 3  4 |
`------'  | 5  6 |     SPST
 |    |   | 7  8 |        /
 |    +---|-9  10|       /
 +--------|-11 12|-----o/   0-----.
          | 13 14|----------------'
          | 15 16|
...etc...

