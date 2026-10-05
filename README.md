# AeroTwin — AI-Enabled Digital Twin for Aero-Piston Engine Health Monitoring

<p align="center">
  <strong>SMART INDIA HACKATHON 2026</strong><br>
  Problem Statement: <strong>SIH26054</strong><br>
  Theme: <strong>Robotics & Drones</strong><br>
  Category: <strong>Software</strong>
</p>

<p align="center">
  <strong>Team: orbit2Ore</strong>
</p>

---

## 🚀 Project Overview

**AeroTwin** is a mission-aware, physics-residual digital twin concept designed for **real-time health monitoring, anomaly detection, fault prediction, degradation assessment, and Remaining Useful Life (RUL) estimation of aero-piston engines used in MALE UAVs**.

The system combines:

- Real-time engine telemetry
- Physics-based engine modelling
- Physics-residual analysis
- Machine learning
- Temporal anomaly detection
- Degradation tracking
- Uncertainty-aware RUL estimation
- Mission/environment awareness
- Post-flight analysis and mission replay
- Edge-first deployment

The central idea is simple:

> **An engine should not be judged only by whether a sensor crosses a fixed threshold. It should also be evaluated against how the engine is expected to behave under its current operating and mission conditions.**

---

# 🎯 SIH 2026 Problem Statement

### Problem Statement ID

**SIH26054**

### Problem Statement

**AI-Enabled Real-Time Digital Twin System for Health Monitoring, Fault Prediction and Mission Reliability Enhancement of Aero Piston Engines used in MALE UAVs**

### Theme

**Robotics & Drones**

### Category

**Software**

### Organization

**DRDO — Department of Defence R&D**

### Team

**orbit2Ore**

---

# 💡 Our Solution

AeroTwin creates a digital representation of the engine that continuously compares:

```text
Observed Engine Behaviour
          │
          ▼
     Digital Twin
          │
          ▼
Expected Engine Behaviour
          │
          ▼
Observed − Expected
          │
          ▼
 Physics Residual
