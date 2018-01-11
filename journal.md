#### ROCO 222
### Motor Mk.1

We built the motor as per the instructions. Our motor has 118 turns of copper wire with an armature resistance of 6.2 Ohms.

![alt text](https://www.instagram.com/p/BaKcMyDDguN/ "Motor Mk.1")

Initially the brushes needed to be held to the commutator but by using folded strips of copper tape and using wire in the fold to help keep it rigid, we could have the brushes sit against the commutator on their own.

When testing, the motor was driven with a power supply set to 9V and 2A. This worked well as shown in the video.

[Video of the motor running.](https://www.instagram.com/p/BZ_vE5WD7hM)

There was however an issue getting the motor running if the coil winding was positioned vertically, due to the magnetic force being unable to provide torque from this position.

### Motor Mk.2

The most important issue to address is the motors inability to provide torque when the armature winding is vertical. We decided to use a hexagonal design with 3 coils instead of one so that, when one of the coils is vertical and torque is lost, the other coils will be in a good position to provide it.

In addition we planned to increase the number of turns in order to increase the performance of the motor as described by the following equation, increasing the number of turns increases the strength of the magnetic field driving the motor B=uNI/l.

Unfortunately we were unable to complete our final design. During the 3D design process we had issues where the motor core section would always be much too large. Any attempts to change the size of the model seemed to be removed upon saving.

### Stepper Motors and Servo Control

During this lab we had to control servos using the arduino, the first piece of code moves the servo back and forth through its full range.

![alt text](https://www.instagram.com/p/Bd0GAmHj-hB/ "Auto")

firstly we had to have the servo move alone in a series of steps (Full, double, Half and micro). The code we used can be found in the following images.

![alt text](https://www.instagram.com/p/Bd0F7S-DDTa/ "Stepper")
![alt text](https://www.instagram.com/p/Bd0F87jjSMd/ "Stepper")
![alt text](https://www.instagram.com/p/Bd0F-_sDzwl/ "Stepper")

This code activates the motors magnets in series in order to achieve the desired result i.e. smaller increments of movement.

We then moved to have the servo operate using the Potentiometer, we used the code below.

![alt text](https://www.instagram.com/p/Bd0GCOEjIaW/ "Pot movement")

[Video of the servo operated with Potentiometer.](https://www.instagram.com/p/Bdz1pbJDdxg/)

### Robot Arm

Our final task was to design and build a robot arm with 2 degrees of freedom, controlled via the servos using ROS.

The design process was difficult as our initial design was too heavy and used too much material to be printed, forcing a redesign. 

We began using ROS in an attempt to get the 3D model onto rviz. 

![alt text](https://www.instagram.com/p/Bd0Iv7zDqGz/ "ROS")
![alt text](https://www.instagram.com/p/Bd0I1MujoC0/ "Rviz")

