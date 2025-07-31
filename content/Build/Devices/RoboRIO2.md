The RoboRIO2 is the current control system for [[FIRST Robotics Competition]] robots, supplanting the [[RoboRIO]].  The RoboRIO2 is set to be replaced by [[SystemCore]] in 2027.

![[images.jpeg| 400]] 

# RoboRIO2 Hardware Specifications
- DDR3 Memory: 512MB
- Nonvolatile Memory: 16MB onboard, 4GB microSD
- Digital I/O Ports: 10
- PWM Ports: 10
- USB-A Ports: 2
- CAN loops: 1
- Ethernet for connectivity
- USB 2.0 for writing software

# RoboRIO Wiring
The roboRIO2 gets power from a 10 A fused port on a [[Power Distribution Hub]] or [[Power Distribution Panel 2.0]].  A [[Robot Status Light]] is wired to the RSL port, and a [[VH-109]] or [[OM5P-AC]] radio is connected with an ethernet cable to the ethernet port.  The CAN loop starts from the RoboRIO, and connects to any devices in the loop.

![[frc-control-system-layout-rev.svg]]