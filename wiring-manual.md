
    
    Enable the board by placing a jumper on those two pins.



    Place jumpers on the micro step resolution for each driver, I'm using a DRV8825 driver and I'll select M1. I consulted the table I found inside this document on page 8: https://bulkman3d.com/wp-content/uploads/2019/04/CNC-Shield-Guide-BM-v1.0.pdf



    Place the stepper drivers in their designated places.



    Connect the stepper motors to the pins next to the drivers, the orientation isn't important since it can be configured in the software if the motor is spinning the wrong way.



    Connect the limit switches.



    Connect the laser. The laser should have the pins labeled on the PCB. The 12V + and - wires should go to the PSU or the 12V screws terminal on the CNC shield. The third wire which carries the PWM signal goes to the Z+ or Z- limit switch pin.



    Connect the PSU.

