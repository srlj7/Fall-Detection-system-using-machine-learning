# Smart Fall Detection System (FDS) 

###  Project by: [Saif Asaad Naeem, Mustafa Saleh Gouda, Hussein Ali Mohsen]
**Institution:** Almaaqal University, College of Engineering, AI Department, Second year
**Year:** 2025

---

## Overview
This project presents a wearable Fall Detection System tailored for the elderly. It utilizes an **Arduino Pro Mini** and **GY-87 sensor (MPU6050)** to monitor movements in real-time. The system processes data using a **Decision Tree** algorithm optimized for embedded systems, distinguishing between daily activities (Walking, Praying, Sitting) and actual falls with **95% Recall**.

##  Hardware Components
* Microcontroller: Arduino Pro Mini
* Sensor: GY-87 (MPU6050 Accelerometer + Gyroscope)
* Communication: HC-12 Wireless Module
* Power: 3.7V Li-ion Battery

## Machine Learning Approach
* Algorithm: Decision Tree (Post-Pruned).
* Optimization: The model outperformed XGBoost and SVM in terms of hardware efficiency and balanced accuracy.
* Features Extracted: Acceleration maximum, Acc minimum, Acc mean, Acc range, Acc variance, Gyroscope Maximum, Gyro mean, Pitch Angle.
* Key Achievement: Successfully distinguishing Islamic prayer movements (bowing and prostrating) from falls to reduce false alarms.

##  Repository Structure
* `Arduino_Code`: The C++ firmware deployed on the Pro Mini.
* `Python_ML`: Scripts for data processing, training, and testing (XGBoost, DT, etc.).
* `Dataset`: Raw CSV files collected from real-world experiments.
* `Research_Paper`: The full documentation and scientific paper of the project.

---
*© 2025 All Rights Reserved.*
