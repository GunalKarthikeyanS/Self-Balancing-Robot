# 🤖 Self-Balancing Robot
### 2nd Place Winner — ARC'23 Robotics Competition, Hindustan University

A two-wheeled self-balancing robot built from scratch using PID control algorithms and real-time sensor fusion. Competed and secured **2nd place at ARC'23** (Autonomous Robotics Competition) held at Hindustan University, Chennai.

---

## 🏆 Achievement
- **2nd Place** at ARC'23 — Autonomous Robotics Competition, Hindustan University, Chennai
- Built entirely from scratch by a team of 3
- Demonstrated real-time dynamic stability under competition conditions

---

## 🛠️ Tech Stack

| Component | Details |
|---|---|
| Microcontroller | Arduino |
| IMU Sensor | MPU6050 (6-axis gyroscope + accelerometer) |
| Control Algorithm | PID (Proportional-Integral-Derivative) |
| Motor Driver | L298N H-Bridge |
| Chassis | Custom 3D-modelled and printed |
| Programming Language | C++ |

---

## ⚙️ How It Works

The robot maintains balance by continuously reading orientation data from the MPU6050 IMU sensor and applying a PID control loop to adjust motor speed and direction in real time.

```
MPU6050 IMU Sensor
    ↓
Raw Accelerometer + Gyroscope Data
    ↓
Complementary Filter — combines accel + gyro for stable angle estimate
    ↓
PID Controller — calculates correction based on error from 0° setpoint
    ↓
Motor Driver (L298N) — applies correction to left and right motors
    ↓
Robot stays balanced
```

### PID Control
- **P (Proportional):** Corrects based on current tilt angle
- **I (Integral):** Corrects accumulated error over time
- **D (Derivative):** Dampens oscillations for smooth response

---

## 🔧 Hardware Components

- Arduino Uno/Nano
- MPU6050 IMU (Inertial Measurement Unit)
- 2x DC Gear Motors
- L298N Motor Driver Module
- 2x Wheels
- LiPo Battery
- Custom 3D printed chassis
- Jumper wires and connectors

---

## 📐 Chassis Design

The chassis was fully designed and 3D modelled by the team, optimized for:
- Low center of gravity
- Balanced weight distribution
- Compact motor and battery placement

---

## 👥 Team

Built by a team of 3 students from Easwari Engineering College, Chennai as part of the BE in Robotics and Automation program.

---

## 🎓 Academic Context

**Institution:** Easwari Engineering College, Chennai, India  
**Program:** Bachelor of Engineering, Robotics and Automation  
**Period:** August 2022 – March 2023  
**Competition:** ARC'23, Hindustan University, Chennai
