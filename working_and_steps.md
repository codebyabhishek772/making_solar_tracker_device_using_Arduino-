# making_solar_tracker_device_using_Arduino-
solar tracker device using Arduino


Components Required

1) Arduino UNO  [Buy Here]
2) Servo Motor  [Buy Here]
3) Light Sensors
4) LDR
5) Resistors

Working
LDRs are used as the main light sensors. Two servo motors are fixed to the structure that holds the solar panel. The program for Arduino is uploaded to the microcontroller. The working of the project is as follows.

LDRs sense the amount of sunlight falling on them. Four LDRs are divided into top, bottom, left and right.

For east – west tracking, the analog values from two top LDRs and two bottom LDRs are compared and if the top set of LDRs receive more light, the vertical servo will move in that direction.

If the bottom LDRs receive more light, the servo moves in that direction.

For angular deflection of the solar panel, the analog values from two left LDRs and two right LDRs are compared. If the left set of LDRs receive more light than the right set, the horizontal servo will move in that direction.

If the right set of LDRs receive more light, the servo moves in that direction.

Setup of this project

Step-1

1) Take cardboard. Make a hole in the middle and four holes on four sides so that LDR fit into that.
2) Stick the solar panel to the cardboard and bring two wires of the panel out.

Step 2

1) Now cut one of the two leads of the LDR so that one lead is shorter and other is longer.
2) Insert these four LDRs into four holes as shown.
3) Bend the straight Perforated metal strip.
4) Place the bent metal strip on the back side of the cardboard
5) Apply glue to the LDR to fix them firmly.

Step 3

1) Solder the two leads of LDR.
2) To the other ends of LDR Solder resistors of 10k ohm
3) Join the four leads of the 4 LDRs by connecting with a wire.


Step 4

1) Now take a bus wire.This is used to connect the Outputs of four LDRs to Arduino board.
2) Insert it into metal strip as shown in the image.
3) Now Solder the four wires to four LDRs at any point between LDR and resistor.


Step 5

1) Insert another two wire bus into the perforated metal strip as shown.This is used for supplying Vcc and GND to LDR circuit.
2) Solder one wire to the leads of LDRs which are connected to resistors and other wire to the other leads.
3) Short the leads of LDRs connected to resistors using a wire.

Step 6

1) Now connect a servo motor to the Perforated metal strip using Screw.
2) Apply glue to the servo to fix it firmly.


Step 7

1) Take another straight Perforated metal strip and bend it.

Step 8

1) Now place the set up of solar panel and first servo motor to the metal strip of second servo motor 
