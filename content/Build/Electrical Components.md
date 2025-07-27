[[FIRST Robotics Competition]] robots are composed of a large amount of electronics devices to run and control the different functions of the robot.

# Control System
The control system is the brains of the robot.  It runs the code created by the [[Programming Team]], processing inputs from sensors around the robot, and sending commands to motors and other devices.
## Devices
- [[RoboRIO]]
- [[RoboRIO2]]
- [[SystemCore]]
- [[CANivore]]
- [[Robot Status Light]]

# Power Distribution
Power for the robot comes from one larger 12V battery, and must be spread out thought the robot to ensure that all the devices onboard get the power that they need and provides surge and overcurrent protection to the devices.
## Devices
- [[Power Distribution Hub]]
- [[Power Distribution Panel 2.0]]
- [[120 Amp Breaker]]
- [[Voltage Regulation Module]]

# Radio
The radio connects the robot to the driver station during practice, and to the field during competitions. 
## Devices
- [[Vivid Hosting VH-109]]
- [[Open-Mesh OM5P-AC]]

# Motors and Controllers
Motors are how the robot moves around the field and drives the mechanisms to interact with game elements and the field.  Each motor needs a controller to translate signals from the control system to voltage applied to the motor.
## Devices
Devices are divided into motors and controllers, however some motors may have their controllers integrated.
### Motors
- [[Kraken x60]]
- [[Kraken x44]]
- [[Falcon 500]]
- [[Minion]]
- [[NEO Vortex]]
- [[NEO 550]]
- [[NEO V 1.1]]
- [[CIM]]
- [[Mini CIM]]
- [[775]]
### Controllers
- [[Talon FX]]
- [[Victor SPX]]
- [[Talon SRX]]
- [[Talon FXS]]
- [[Spark Max]]
- [[Spark Flex]]

# Vision
Vision uses onboard cameras to observe the field and the game pieces to determine the robots location on the field, and the relative location of objects, making it possible to have to robot path to a location automatically.
## Devices
- [[Limelight]]
- [[Orange Pi]]
- [[Arducam Camera]]

# Sensors
Robots use a variety of sensors to gain data about the position of mechanisms and game pieces inside of the robot.
## Devices
- [[Line Break Sensor]]
- [[CANcoder]]
- [[CANrange]]
- [[Limit Switch]]

# Servos
Servos are a type of motor that use their own feedback loop to reach a position set in the robot code.  
## Devices
- [[Servo Hub]]
- [[Servo Power Module]]
- [[Swyft Servo]]
- [[Axon Mini]]
- [[Axon Max]]

# Pneumatics 
Pneumatics use air pressure instead of electronic power to move components of the robot 
## Devices
There are two main types of electrical devices when it comes to pneumatics.  The controllers, which takes electrical commands from the control system and translates them to other devices, and pressure devices that create and use air pressure.  
### Controllers
- [[Pneumatics Control Module]]
- [[Pneumatics Hub]]

### Pressure Devices
- [[Compressor]]
- [[Solenoid]]
