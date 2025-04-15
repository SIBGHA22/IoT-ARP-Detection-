 IoT ARP Spoofing Detection using ML (SVM/KNN)

This project presents a lightweight, ML-based framework (SVM & KNN) optimized for detecting ARP spoofing attacks in IoT environments. The system is tested on real-world datasets (IoTID20 & CICIoT2023) and deployed on edge devices like Raspberry Pi.

## Features

- 96.2% Accuracy on spoofing detection
- Uses 23 IoT-specific features
- Real-time detection with <10ms latency
- Benchmarked against traditional solutions (e.g., ARPWatch)
- Includes a novel Time-to-Mitigation (TTM) metric

## Datasets Used

- [CICIoT2023 Dataset](https://www.unb.ca/cic/datasets/iotdataset-2023.html)
- [IoTID20 Dataset](https://sites.google.com/view/iot-network-intrusion-dataset/home)

## Model Comparison

| Model               | Accuracy | F1-Score | Latency (ms) |
|---------------------|----------|----------|---------------|
| SVM                 | 96.2%    | 0.962    | 8.1 ms        |
| KNN                 | 92.1%    | 0.921    | 5.2 ms        |
| ARPWatch (Baseline) | 82.1%    | 0.69     | >100 ms       |

## Installation

```bash
git clone https://github.com/yourusername/IoT-ARP-Detection.git
cd IoT-ARP-Detection
pip install -r requirements.txt# IoT-ARP-Detection-
