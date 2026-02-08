🛠️ Project Title: **Intelligent-Elevator-control-Model**
From Schematic to Structural Reality

**Phase 1: Logic & Schematic Design (The Brain)**

I started by designing the Control Logic using a specialized circuit (as seen in my documentation).![IMG_20250407_172116_827](https://github.com/user-attachments/assets/b307576b-87f7-44a9-8479-70a0d1d38166)

**The Challenge:**

Creating a system that could prioritize multiple floor calls without "glitching" or skipping levels.

**The Solution:**

I engineered a Microcontroller-based logic using Interrupt-driven programming in Embedded C.

I integrated NPN/PNP transistors in an H-Bridge configuration to manage the motor's bi-directional movement (Up/Down) with precision.

**Phase 2: Mechanical Fabrication (The Skeleton)**

![IMG_20250407_172037_566](https://github.com/user-attachments/assets/9a86c969-6580-4942-a025-b933cc19357f)

Using the "Rear View" documentation, I moved from the breadboard to the physical frame.

**Linear Actuation:**

I chose a threaded lead-screw mechanism (visible in the rear-view photo) to convert the high-speed rotation of the DC motor into stable,
high-torque vertical lift. 

**Structural Integrity:**

I fabricated the main chassis using lightweight but rigid materials to ensure zero-wobble during cabin transit. 

**Sensor Integration:**

I strategically mounted IR Proximity Sensors at each floor level. 

These act as the "eyes" of the system, sending a stop signal to the brain the moment the cabin aligns with the floor. 

**Phase 3: The "Data" Evolution (System Intelligence)**

As a Systems Data Analyst, I designed this prototype to be more than just a lift; it's a data source.

**Optimization:** 

By tracking the time taken between floors, I can analyze the Motor Efficiency and identify potential friction points in the lead-screw.

**Future Vision:**

I am currently developing a Predictive Maintenance Dashboard in Power BI that uses this sensor data to alert operators before a mechanical failure occurs.
