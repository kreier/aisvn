# AISVN Robot Platform

Platform standards for robot builds at AISVN

## Robot platform

This defines the location for the 4 mount points M3 to connect the drive unit to the control unit

## Function drive()

A standardized software function that can be tailored to the used CPU and motor to be interchangeble if you switch bases or control units

## Remote interface

To control the robots we have a serial interface to receive signals from bluetooth or WiFi or even a cable controller that is interpredet by the control unit to drive the robot. Since there are many remote control apps available and even different bluetooth standards, we had to standardize the interface to work with this variety. And not all apps are available both on Android and iOS.

## History

Back in 2018 we started to build our first remote controlled robots during club time at the AISVN. With ASA we've come a long way after that.

### T500

The base has 3 motors with encoders and the robot is controlled by a raspberry Pi 3 with a 7" IPS screen and a camera with object detection. Might be upgraded to a NVIDIA Jetson Nano, but that's all future.

### T400
<img src="https://github.com/kreier/T300/raw/master/docs/T400-20191119.jpg" width='30%' align='right'>

In session 3 for ASA this year we upgraded both motor unit and control unit. Now we have 12V DC motors that work much better with PWM and slow rpm. And it is controled by the much more powerful esp8266. With included WiFi. And we can program it with micropython. 

#### REPL
Another advantage: We now have REPL - the time from program instruction to execution is down to less than a second!

### T300
<img src="https://github.com/kreier/T300/raw/master/docs/T300-20191119.jpg" width='30%' align='right'>

For the second ASA session 2019/2020 we upgraded our robot car with a 4 DOF robot arm. The code had to be expanded as well.

It also includes an ultrasonic sensor for distance now. This was backported to ASA as well.

### ASA robot
<img src="https://github.com/kreier/T300/raw/master/docs/asa-20191119.jpg" width='30%' align='right'>

Time to get serious. 10 students signed up for ten Monday evening sessions to build their own robot car. At the end 6 working robots were produced.

### T200
<img src="https://github.com/kreier/T300/raw/master/docs/T200-20191119.jpg" width='30%' align='right'>

Now with PWM and controlled by an

### T100

To inspire the work for my bigger cohort of 21 students for the second semester 2017/2018 I created an example robot that was on display in our future Makerspace location.

<img src="https://github.com/kreier/T300/raw/master/docs/T100-20191119.jpg" width='30%' align='right'>

### Arduino Club 2017

When I started at AIS we had a weekly time slot of 30 minutes to work on a club of your choice. With 8 members we took our first steps in Arduino programming and blinking LEDs.

And we [tweeted](https://twitter.com/matthiashcmc/status/971250335628046337) about it.
