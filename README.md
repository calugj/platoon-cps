Boscolo Meneguolo Luca — Cybersecurity Master Degree
# Cyber Physical Systems and IoT Security

## *Replay Attack Detection in a Platoon of Connected Vehicles with Cooperative Adaptive Cruise Control*

[Cooperative ACC](https://en.wikipedia.org/wiki/Cooperative_Adaptive_Cruise_Control) is the direct follow-up of the Adaptive Cruise Control, a device that allows to keep a desired headway to the preceding vehicle.
This technology can be used to setup platooning, a sequence of vehicles where one follow each other adaptively at safe distance.
This will in turn reduce traffic, as the platoon is managed by fast-responsive controllers, and possibly reduce the pollution by increasing the aerodynamic efficiency.
However, as we delegate human responsibility to machines, attacks can be attempted to harm the stability of the system, by degrading the performance or causing severe accidents.
In this work, we will refer to the [paper](https://ieeexplore.ieee.org/document/8431538) to demonstrate the usage of a basic platooning simulator to determine how replay attacks are implemented, and a possible solution that can detect them.
Moreover, an extension on the authors' work was conducted to explore the possibility for a lightweight implementation of the detection algorithm and possible attacks to the countermeasure.

The lineup is the following:
- Build a basic platooning simulator,
- Perform a replay attack,
- Attack detection,
- Analysis on the feasibility of the optimization strategy,
- Attacks from the leader.




typst watch ./src/report/platoon.typ ./Report.pdf