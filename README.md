# RoboSapiens_repo


What makes our bot different:
The basic concept behind our bot is 'modularity'. 
Modularity means the degree to which parts can be interchanged and replaced efficiently. 
We chose to assemble our components on a breadboard instead of a fretboard. 
This allowed for easy replacements of parts and changing of circuits. It also allowed us more freedom to orient the components until the very end. 
It also allowed for much easier debugging and code addition. Moreover, it saved us the hassle of soldering and significantly reduced time consumption.
For each problem statement we took part in, we had additional modules. 

For problems that required sensing distance, we had a sensor module that we could equip for that statement and then remove once we needed to use our bot for a different problem statement.

For the AUV mechanical problem statement, we attached a 'carrier' module that could help carry the obstacle up the incline. 
It consisted of pieces of cardboard cut out to hold the obstacle while still staying under the 25x25 dimension limit. 
These pieces of cardboard were connected to Mechanix bars that were screwed into the metal chassis using nuts and bolts using the inbuilt holes in the metal chassis, once again reinforcing our decision to take a white metal chassis.

A radical innovation made during the project was the parabolic reflector sensor module. This module contains one HC-SR04 ultrasonic sensor, a parabolic plane reflector and a hyperbolic plane reflector arranged in a Cassegrain telescope configuration. 
Unfortunately, the performance fell slightly short of what we needed due to time and material constraints. Thus, we had to use two sensors instead.


Bot components: White metal chassis, four motors (100 rpm) along with nuts to fit, four wheels, one L298N motor driver, one breadboard (medium-sized), esp32, connecting wires (MM, MF, FF), 2 HC-SR04 ultrasonic sensors, soldering kit, wire cutter nuts and bolts (that fit metal chassis holes)
Procedure: Assemble the bot according to the image

The main reason we focused on modularity is due to the metal chassis. The members of the team were quite busy over the weekend and the week, so we could not afford to meet all the time and work on the project. Thus, we chose a metal chassis as it requires minimal effort to get running. However, the disadvantage of the metal chassis is the lack of customisability. This was why we did not take part in the MRT mech statement, as that required a lot of additional features to add to the chassis themselves. In order to counter the lack of customizability, we chose modularity. This allowed us to add many more features while keeping the base chassis structure unchanged.
