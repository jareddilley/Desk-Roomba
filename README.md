# Desk-Roomba
![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/desk-roomba-main-demo-3.gif)

Miniaturized Roomba that can dust all your surfaces. This is a fully 3D-printed robot that can avoid objects, avoid falling off the edge of a table, and dust the surface as it goes. The idea was built off of the SMARs robot that can be found on Thingiverse (https://www.thingiverse.com/thing:2662828). I made some additions of my own to better suit my needs. This creation has a YouTube video as well so those who are visual learners can be entertained: https://www.youtube.com/watch?v=fM7q85V_2Z0

![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/roomba-schematic.PNG)

Full Arduino schematic for anyone trying to build the project. If there are any confusions feel free to ask in the comments.

# Object Detection
![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/ultrasonic-sensor-demo.gif)

The robot can avoid objects by using an ultrasonic sensor. This was the only sensor already built into the original design. The sensor bounces ultrasonic sound off of objects and listens back for the echo. The time between send and receive determines the distance. In code, we can vary how close the object can get before turning around. 

# Edge Detection
![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/ir-sensor-demo.gif)

The robot can keep itself from falling off the edge by using two ir sensors. The sensors reflect infrared light off of the table or ground and if the IR light does not reflects back we know we are about to fall off of the table. Two sensors are used to check both corners of the robot so that no matter the angle the robot comes in at it can sense the edge in time.

# Duster
![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/dusting-demo.png)

The duster is a simple microfiber towel that is attached to a sweeper. The fabric is held in with wedges: this follows the idea of a sanding block to keep the sandpaper in place while under friction. The broken-down 3d model can be seen below:

![image](https://github.com/jareddilley/Desk-Roomba/blob/main/Media/duster-3d-model.PNG)

With this design, multiple add-ons could be created to make this modular robot quite robust.
