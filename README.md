# 🤖 Self-Balancing Robot – MATLAB & Simulink

This project presents the design and simulation of a **Self-Balancing Robot** using **MATLAB & Simulink**, based on the concept of an **inverted pendulum**.  
A **PID Controller** is implemented and tuned to stabilize the robot and maintain its upright position under different conditions.

---

## 📌 Project Overview

The self-balancing robot is a classic control problem that demonstrates the behavior of unstable dynamic systems.  
In this project, the robot dynamics were modeled, simulated, and controlled using classical control techniques.

---

## ⚙️ System Description

- The robot is modeled as an **inverted pendulum on a cart**.
- A **PID controller** is used to regulate the tilt angle.
- The controller parameters are tuned to achieve:
  - Fast response
  - Minimum overshoot
  - Stable behavior

---

## 🛠 Tools & Technologies

- MATLAB  
- Simulink  
- Control System Toolbox  

---

## ✨ Features

- Dynamic modeling of the self-balancing robot.
- Complete control system design using Simulink.
- PID controller implementation and tuning.
- Stability and performance analysis.
- Simulation under different initial conditions and disturbances.

---

## 📊 Control Strategy

- Controller Type: **PID Controller**
- Control Objective:
  - Maintain robot balance (upright position).
  - Minimize steady-state error.
  - Reduce oscillations and settling time.

---

## 🚀 How to Run the Simulation

1. Open MATLAB.
2. Navigate to the project folder.
3. Open the Simulink model file:
self_balancing_robot.slx

4. Run the simulation and observe the system response.

---

## 📈 Results

- The robot achieves stable balancing behavior.
- The PID controller successfully stabilizes the inverted pendulum.
- Smooth response with acceptable overshoot and settling time.

---

## 🔮 Future Improvements

- Add **IMU sensor fusion** (Accelerometer + Gyroscope).
- Implement advanced control methods:
- LQR
- State-Space Control
- Real-time implementation on embedded hardware (Arduino / STM32).
- 3D visualization and hardware-in-the-loop (HIL) simulation.

---

## 👤 Author

**Mohammed Qumash**  
Mechatronics Engineering Student  
Interested in Robotics, Control Systems, and Automation

---

## 📄 License

This project is open-source and available for educational and research purposes.
