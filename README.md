# DualSec: AI-Powered Secure Monitoring System

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green.svg)](https://opencv.org/)
[![Hackathon](https://img.shields.io/badge/Type-Hackathon_Winner-orange.svg)]()

> **Role:** Team Leader & Lead Engineer  
> **Tech Stack:** Python, OpenCV, Face_Recognition, SQL

## Overview
DualSec is a biometric security platform designed to enforce strict single-user authentication. It addresses vulnerabilities such as credential sharing in secure environments by implementing real-time facial recognition and anomaly detection.

The system achieves **98% recognition accuracy** and includes a live dashboard for visualizing access logs and alerting administrators to unauthorized database modifications.

## System Architecture
The pipeline integrates computer vision for perception with a backend logging system for audit trails. The architecture consists of:

- Facial recognition module (Python + OpenCV + Face_Recognition)
- Real-time anomaly detection engine
- Secure SQL backend with verification layer
- Dashboard for audit visualization

## Key Features
1. **High-Accuracy Biometrics:** Optimized facial recognition algorithms resilient to varying lighting conditions, achieving **98% accuracy**.
2. **Real-Time Anomaly Detection:** Flags unauthorized login attempts and "tailgating" events instantly.
3. **Audit Trail Visualization:** Dashboard highlights temporal patterns and anomalies in access logs.
4. **Secure Database Integration:** Prevents unauthorized SQL modifications using a deterministic verification layer.

## Installation & Usage

Clone the repository:

```bash
git clone https://github.com/simyikong/DualSec.git
cd DualSec
