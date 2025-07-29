The RoboRIO was the control system for [[FIRST Robotics Competition]] robots from 2015 to 2021, when it was supplanted by the [[RoboRIO2]]. 

![[roborio.jpeg]] 

# RoboRIO Hardware Specifications
- DDR3 Memory: 256MB
- Nonvolatile Memory: 512MB
- Digital I/O Ports: 10
- PWM Ports: 10
- USB-A Ports: 2
- CAN loops: 1
- Ethernet for connectivity
- USB 2.0 for writing software

# RoboRio Wiring
The roboRio gets power from a 10 A fused port on a [[Power Distribution Hub]] or [[Power Distribution Panel 2.0]].  A [[Robot Status Light]] is wired to the RSL port, and a [[Vivid Hosting VH-109]] or [[Open-Mesh OM5P-AC]] radio is connected with an ethernet cable to the ethernet port.  The CAN loop starts from the RoboRIO, and connects to any devices in the loop.

![[frc-control-system-layout-basic.svg]]