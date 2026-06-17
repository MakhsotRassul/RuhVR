Engineering and technical specification of the RuhVR robot
Kinematic structure and actuators:
The RuhVR robot is built according to an anthropomorphic scheme with functional units 3D-printed based on open concepts.
The right hand manipulator possesses 5 degrees of freedom. Five independent servo drives control the flexion and extension of each finger via linkages. The purpose is to generate complex gestures of greeting, pointing at objects, and demonstrating emotional states.
The elbow joint uses 1 high-torque servo drive, such as the MG996R, providing the raising and lowering of the forearm along the vertical axis to simulate human dynamics.
The neck unit includes 1 servo drive responsible for turning the head along the horizontal axis to redirect attention to the interlocutor.
The mobile platform is a differential chassis driven by 4 independent DC motors with gearboxes and wheels to move the robot within the plane of the room.
Electronic components and power distribution system:
It is used to offload and ensure smooth current to the servo drives.
The power supply system uses separate circuits. The controller logic is powered independently, while the power section of the servo drives and DC motors is powered from an external source through voltage regulators to eliminate voltage drops and interference.

Implementation of autonomy according to Rule 5.1 of the WRO competition:
The control of the robot completely excludes the use of remote control panels or rigid timings.
