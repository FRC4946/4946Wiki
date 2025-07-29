The Power Distribution Hub made by REV is a main power distribution device for use on [[FIRST Robotics Competition]] robots.

![[REV-11-1850-Power-Distribution-Hub-Hero-FINAL__29576.jpeg|400]]

# Power Distribution Hub Hardware Specifications
- Large WAGO Power Ports: 20
- Small WAGO Power Ports: 4
- CAN terminals: 2 sets

## Breaker Sizes
- ATO auto resetting breakers: 10 A, 20 A, 30 A, 40 A
- ATM fuse: 1 A, 2 A, 5 A, 10 A, 15 A 


# Power Distribution Hub Wiring
The Power Distribution Hub main power supply is connected to the battery and [[120 Amp Breaker]].  The Power Distribution Hub must be connected to the CAN bus started at the [[RoboRIO]] or [[RoboRIO2]].  Smaller amperage devices like[[RoboRIO]] or [[RoboRIO2]], [[Vivid Hosting VH-109]] radio, etc. are connected to the smaller WAGO terminals, and larger devices like motors ([[Kraken x60]], [[Kraken x44]], etc.) are connected to the larger WAGO terminals.

![[frc-control-system-layout-rev.svg]]