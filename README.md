##Color-Based Object Sorting System using Vision Sensors and Comparator Logic

This repository contains the simulation files and logic setup for an industrial automation project titled "Color-Based Object Sorting System using Vision Sensors and Comparator Logic." The objective of this system is to automatically detect and sort objects on a conveyor belt based on their color (Blue, Green, and White) using Factory I/O and Control I/O software.

🧠 Project Overview
The system employs vision sensors to detect the color of passing objects on a conveyor belt. When a specific color is identified, a comparator block processes the color data and triggers a pneumatic pusher to redirect the object into its respective bin. Each color has a dedicated detection and sorting path.

The system design includes:

A single conveyor belt that carries color-coded objects.

Vision Sensor 1 (VS1) placed before the separator to detect the incoming color.

Comparators to match detected color data (e.g., Blue = 11, White = 13, Green = 15).

Set-Reset (SR) Latches to hold sorting signals while the object is in motion.

Vision Sensor 2 (VS2) placed after the separator to reset the latch once sorting is complete.

Pneumatic pushers controlled by boolean outputs to divert objects to correct bins.

⚙️ Features
Real-time color detection using Factory I/O Vision Sensors.

Minimal error rate in classification using comparator-based logic.

Efficient use of boolean logic in Control I/O for controlling actuators.

Scalable design adaptable to more object types and colors.

🛠️ Tools and Technologies
Factory I/O – Simulation environment.

Control I/O – Logic implementation and I/O interface.

Vision Sensors – For object color detection.

Pneumatic Pusher – For sorting objects.

📈 Future Scope
This project can be expanded with:

AI-based image processing for detecting mixed or unknown colors.

Integration with SCADA systems for remote monitoring.

Enhanced sorting algorithms for high-speed conveyor systems.
