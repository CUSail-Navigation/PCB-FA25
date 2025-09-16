# CUSail FA25-SP26 PCB Suite

Here are the files for the three main PCBs designed during the FA25-SP26 academic year. These were all designed with KiCad due to its support across all operating systems and our use cases not requiring more sophisticated PCB design tools.

These PCBs were designed with the idea that the boat would contain two electronics boxes - one for digital electronics, and the other for power electronics. The decision to split them was made because it is unlikely that one would need to work on both simultaneously (thus making the electronics physically easier to work with), reduces cable clutter, and reduces the likelihood of every part of the system getting drenched in water in the event that the boat capsizes. 


## Electronics PCB

This PCB houses the digital electronics found on the boat. This includes the main microcontroller(s), sensors, radio transmitters/recievers, and interfaces to other parts of the boat which rely on computations. This PCB sits in the digital electronics box.

## Power Distribtuion PCB

This PCB contains the circuitry necessary for stepping down and distributing power supplied from our 22.2V LiPo battery. This PCB sits in the power electronics box.

## Battery Management System PCB

Because we use a LiPo battery, battery failure is possible of the battery discharges too much. This PCB is responsible for monitoring the state of the battery and cutting power in the event that it discharges too much. This PCB is housed in the power electronics box.
