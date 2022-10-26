
The pyboard has a processor much better than commercial flight controllers, so we can made a flight controller similar or better written in python.

The main.py is based is this link:
http://owenson.me/build-your-own-quadcopter-autopilot/

The mpu6050.py is a modified version from here:
https://github.com/cTn-dev/PyComms/tree/master/MPU6050

The pid.py is based from here:
https://github.com/diydrones/ardupilot

To receive the PWM from the RC receiver, I took the code from here:
http://wiki.micropython.org/platforms/boards/pyboard/modpyb/Timer-Examples



COMPONENTS
1×pyboard
micropython board
1×FrSky receiver
2.4 GHz receiver with telemetry
1×FrSky transmiter
2.4 GHz transmiter with telemetry
1×mpu6050
3-axis accelerometer and 3-axis gyroscope

Credit to Credit to https://github.com/wagnerc4/flight_controller

