---

title: Line Follower Robot
meta: An autonomous robot that can follow a line.
category: projects
---
#A Line Follower Robot
A line follower robot is one of the simple robots that one use to start as their interest.

It is a simple robot that can follow a colored line on a smooth surface of different color. The paths can be like some shown below:

###So, a line follower robot works as follows:
>• The IR-sensors can detect difference between the light and dark colour(for our case it was white surface and black line on it), and are powered from the controller board.
>
>• The controller board continuously reads the analog input from the IR-sensors and knows about the position of the robot by knowing the readings of differently positioned sensors.
>
>•The controller then decides which direction it should choose and accordingly sends the PWM signals to the motor driver circuit which makes the bot to follow the line.
<img src="../../LFRblock.png" width="641" height="546" alt="Block Diagram" title="Working of LFR" />