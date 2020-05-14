 # Insect Bot
 * [Basic Info](#basic-info)
* [Assembling](#assembling)


# Basic Info
Well, what is the Insect Bot. Actually it's not really an insect because it only has four legs, insects does have six of them, right? However, the robot got the name because of his shape with the thin wire legs and the IR sensor rosed up.


That robot already has a long history. first I built one with standard servos and an Arduino UNO but soon I wanted it smaller and even more easy to build. After a couple of attempts with different designs this one is the final one.

## Preview
![He's walkin](ezgif.com-video-to-gif.gif)



## You need these parts
Here are the Component required for building this project. The list is quite a simple one :

-Double side tape
-Wire strippers
-Nose plier
-PCB
-Ultrasonic sensor
-Arduino uno
-Cable tie
-Servo motor
-Screw drvier
-Wire (for the legs)
-Connecting wire
-Battery
So once you have all the components ready, Lets gear up!!!

## Assembling
So the chassisof the robot is designed depending on the type of Servo motor used (small , large ), but I have used a smaller one. That's OK if you are using a larger one, both run on the same principle.

So the very first step is to attach a double side tape to the back of the first Servo motor. Then attach the second servo motor to the first servo in such a way that the motor axle of the second motor should face downward.

FRONT LEGS : Bend the wire in a V shape. you will have to bend them later in the right shape anyway.The bending quality depends on the wire you are using. So please bend it as close to the pliers edge as possible

RARE LEGS:  Place the wire into the holes provided into the servo horn, then bend the wire as shown in pictures using pliers . If you have any doubt in this steps? feel free to comment below i will glad to help you out.

Now fix the legs to the servo motor with the help of a screw driver.


So the connection is as follows :-

the dark color wire(brown wire) of the servo is connected to the 5V pin of the Arduino.
the medium color wire(red wire) of the servo is connected to the ground pin of the Arduino.
the light color wire(yellow wire) of the servo is connected to the digital pin of the Arduino
the connection of a an ultrasonic sensor is as follows :-

the VCC pin is supplied to both digital pin and 5V pins of the Arduino
the ground pin is supplied to the ground pin of the Arduino

![ALT](https://cdn.instructables.com/FNJ/CC30/ICE1TMC6/FNJCC30ICE1TMC6.LARGE.jpg?auto=webp&fit=bounds)

## Programming the Insect Bot

When you are done with the construction. Upload the code in the attachments to your arduino and have with your new robot.



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[wtfpl] https://choosealicense.com/licenses/wtfpl/
