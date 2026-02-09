# 🏗️ Intelligent Elevator Control Model
### *From Schematic to Structural Reality*

## 🎯 Project Overview
This project is a hybrid engineering solution that bridges the gap between **Mechatronics (Hardware)** and **Data Analytics (Software)**. It features a fully functional elevator prototype controlled by an embedded system, designed for precision, safety, and data-driven optimization.

---

## 🧠 Phase 1: Logic & Schematic Design (The Brain)
The core intelligence of the system was developed to handle complex multi-floor requests without conflicts.

*   **The Challenge:** Prioritizing multiple floor calls without "glitching" or skipping levels.
*   **The Solution:** 
    *   Developed **Interrupt-driven programming** in **Embedded C** for real-time responsiveness.
    *   Engineered a **Microcontroller-based logic** to process hall calls and cabin commands.
    *   Integrated **NPN/PNP transistors in an H-Bridge configuration** for precise, bi-directional DC motor control.

---

## 🦴 Phase 2: Mechanical Fabrication (The Skeleton)
Moving from the breadboard to a rigid physical frame to ensure industrial-grade stability.

*   **Linear Actuation:** I utilized a **threaded lead-screw mechanism** (as seen in rear-view documentation) to convert high-speed DC motor rotation into stable, high-torque vertical lift.
*   **Structural Integrity:** Fabricated the chassis using lightweight, rigid materials to eliminate wobble during transit.
*   **Sensor Integration:** 
    *   Mounted **IR Proximity Sensors** at each floor level.
    *   These act as the "eyes" of the system, sending instantaneous stop signals to the MCU when the cabin aligns with the floor.

---

## 📊 Phase 3: The "Data" Evolution (System Intelligence)
As a **Systems Data Analyst**, I designed this prototype to be a source of actionable insights, not just a mechanical lift.

*   **Performance Optimization:** By logging transit time between floors, I analyze **Motor Efficiency** and detect mechanical friction in the lead-screw.
*   **Future Roadmap - Predictive Maintenance:**
    *   Developing a **Power BI Dashboard** to visualize sensor data.
    *   The goal is to implement **Predictive Alerts** that notify operators of potential mechanical failure before it occurs.

---

## 🛠️ Tech Stack
*   **Languages:** Embedded C, Python, SQL
*   **Hardware:** Microcontrollers, IR Sensors, H-Bridge Drivers, DC Motors
*   **Tools:** Power BI (Analytics), Circuit Schematic Tools

---
*Developed by Richard A. Jegede*
