# 🤖 CodeAlpha Robotics & Automation Internship

<p align="center">
  <strong>Robotics • Automation • Sensors • Embedded Systems</strong>
</p>

<p align="center">
  Internship Task Submissions — Task 1 & Task 3
</p>

---

## 📌 Overview

This repository contains my **CodeAlpha Robotics & Automation Internship** task submissions.

The projects demonstrate:

- Robotics and automation fundamentals
- Service robotics research
- Sensor-based automation
- Arduino-based control systems
- System architecture and control logic
- Technical report writing
- Engineering documentation
- Safety considerations for automated systems

---

# 📚 Projects

## 🤖 Task 1 — Service Robots Research Report

### Topic

**Service Robots: Transforming Domestic, Agricultural, and Military Operations**

This research report explores three major areas of service robotics:

- 🏠 Domestic service robots
- 🌾 Agricultural service robots
- 🛡️ Military and defence service robots
- ⚙️ Enabling technologies
- ✅ Benefits and challenges
- 💰 Economic and market impact
- 🔮 Future outlook

### Report Contents

The report includes:

- Introduction
- Domestic service robotics
- Agricultural robotics
- Military and defence robotics
- Robotics technologies
- Benefits and challenges
- Comparative analysis
- Economic impact
- Future outlook
- Conclusion
- References
- Figures and comparison tables

### 📄 Report

[**View Task 1 — Service Robots Research Report**](./Task-1-Service-Robots-Research-Report.pdf)

---

# 💡 Task 3 — Automated Smart Home Lighting System

## System

**Sensor-Based Automatic Lighting with Manual Override**

The project presents an automated smart-home lighting system that uses sensors and a microcontroller to control lighting based on:

- Ambient light
- Human presence
- Manual user control

---

## 🔧 Components Used

| Component | Function |
|---|---|
| **Arduino UNO** | Central controller |
| **PIR Sensor** | Detects human motion |
| **LDR Sensor** | Measures ambient light |
| **Relay Module** | Controls the lighting load |
| **LED Lamp** | Controlled lighting output |
| **5V Power Supply** | Powers the low-voltage electronics |
| **Manual Switch / Mobile Control** | Manual override |

---

## ⚙️ Working Principle

The system combines **ambient light detection** and **human presence detection**.

### Step 1 — Detect Light Level

The **LDR sensor** measures the surrounding light level.

If the environment is sufficiently bright, the lighting remains OFF.

### Step 2 — Detect Human Motion

If the environment is dark, the Arduino checks the **PIR sensor**.

The PIR sensor detects whether a person is present.

### Step 3 — Automatic Lighting

When:

```text
Environment = DARK
        AND
Motion = DETECTED
