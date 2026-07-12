# PrecisionVision

## AI-Based Precision Plastic Component Defect Detection and Quality Inspection System

PrecisionVision is an AI-powered computer vision system developed for automated defect detection and localization in precision plastic components. The project uses the **PaDiM (Patch Distribution Modeling)** anomaly detection algorithm to identify manufacturing defects by learning only from normal product images.

The system is designed for smart manufacturing environments where high precision, zero-defect production, and automated quality inspection are essential.

---

## Project Overview

Traditional quality inspection relies on manual visual checks, which can be time-consuming, inconsistent, and prone to human error. PrecisionVision automates this process using deep learning and anomaly detection techniques to identify defective components with high accuracy.

The system generates anomaly heatmaps that highlight defect locations and automatically classifies products as **Pass** or **Fail**, making it suitable for precision manufacturing industries.

---

## Features

- AI-based anomaly detection
- Defect localization using heatmaps
- One-class learning (training only with normal samples)
- Automated Pass/Fail classification
- High-resolution defect visualization
- Fast industrial inspection workflow
- Suitable for precision plastic manufacturing
- Non-destructive quality inspection

---

## Manufacturing Applications

PrecisionVision can be used for quality inspection of:

- Precision plastic gears
- Injection molded components
- Automotive plastic switches
- Medical plastic devices
- Electronic housings
- Industrial equipment components
- Consumer electronics

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | PyTorch |
| Computer Vision | OpenCV |
| Machine Learning | Scikit-Learn |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Neural Networks | ResNet18 / Wide ResNet50 |
| Algorithm | PaDiM |

---

## Project Workflow

```text
Input Product Image
        │
        ▼
Feature Extraction (CNN)
        │
        ▼
Patch Distribution Modeling
        │
        ▼
Mahalanobis Distance Calculation
        │
        ▼
Anomaly Score Generation
        │
        ▼
Heatmap Generation
        │
        ▼
Pass / Fail Classification
```

---



## Installation

Clone the repository

```bash
git clone https://github.com/Siri-durga/PrecisionVision.git
```

Navigate to the project directory

```bash
cd PrecisionVision
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Dataset

This project uses the **MVTec Anomaly Detection Dataset**, a benchmark dataset widely used for industrial anomaly detection research.

Download the dataset from:

https://www.mvtec.com/company/research/datasets/mvtec-ad/

---

## Running the Project

### Training

```bash
python train.py
```

### Testing

```bash
python test.py
```

### Inference

```bash
python inference.py
```

---

## Output

The system provides:

- Original image
- Predicted anomaly map
- Heatmap visualization
- Defect localization
- Segmentation mask
- Pass/Fail prediction

---

## Future Improvements

- Real-time camera inspection
- Conveyor belt integration
- PLC communication
- Raspberry Pi deployment
- Industrial dashboard
- Production analytics
- Defect statistics
- IoT integration
- Cloud monitoring
- Edge AI deployment

---

## Industrial Applications

- Precision Plastic Manufacturing
- Automotive Industry
- Medical Device Manufacturing
- Electronics Manufacturing
- Smart Factory
- Industry 4.0
- Automated Optical Inspection (AOI)
- Injection Molding Quality Control

---

## Objectives

- Reduce manual inspection effort
- Improve product quality
- Detect microscopic defects
- Minimize manufacturing waste
- Support zero-defect production
- Increase inspection speed
- Improve production efficiency

---

## Author

**Durga Lalitha Sri Varshitha**

B.Tech – Computer Science Engineering

Interested in Artificial Intelligence, Computer Vision, Manufacturing Automation, and Industry 4.0.

GitHub: https://github.com/Siri-durga

---

## License

This project is developed for educational and research purposes. The implementation is inspired by the PaDiM research paper and builds upon publicly available open-source implementations. 
