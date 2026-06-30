# 🌌 AI-enabled Detection of Exoplanets from Noisy Astronomical Light Curves

> An AI-enabled pipeline for automatically detecting exoplanet transit signals from noisy astronomical light curve data using NASA TESS observations.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-success)
![NASA TESS](https://img.shields.io/badge/Dataset-NASA%20TESS-orange)
![BAH 2026](https://img.shields.io/badge/BAH-2026-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📖 Project Overview

Exoplanets are planets that orbit stars outside our solar system. Detecting them through transit photometry is challenging because the brightness variation caused by a planet passing in front of its host star is extremely small and often buried within noisy astronomical observations.

This project presents an AI-enabled pipeline that automates the complete exoplanet detection workflow. The system downloads real NASA TESS light curves, removes instrumental noise, detects periodic transit signals using the Box Least Squares (BLS) algorithm, estimates transit parameters, calculates Signal-to-Noise Ratio (SNR), and classifies potential transit events using Machine Learning.

The objective is to reduce manual effort while improving the reliability and efficiency of exoplanet detection from noisy astronomical light curves.

---

## 🎯 Problem Statement

Develop an AI-enabled data analysis pipeline capable of automatically detecting exoplanet transit signals from noisy astronomical light curve data.

The solution should accurately identify weak transit signatures, suppress observational noise, estimate transit parameters, and classify potential exoplanet candidates using Artificial Intelligence techniques.

---

## ✨ Key Features

- 🚀 Automated NASA TESS Light Curve Download
- 📡 Direct Data Retrieval from the MAST Archive
- 🧹 Noise Removal and Light Curve Flattening
- 🔍 Period Detection using the Box Least Squares (BLS) Algorithm
- 📏 Transit Parameter Estimation (Period, Depth, Duration)
- 📈 Signal-to-Noise Ratio (SNR) Calculation
- 🤖 Machine Learning-based Transit Signal Classification
- 📊 Folded Light Curve Visualization

---

## 🔄 Pipeline Workflow

```text
NASA TESS xCTL Dataset
          │
          ▼
Target Selection
          │
          ▼
Automatic Light Curve Download
          │
          ▼
Noise Removal & Flattening
          │
          ▼
BLS Period Search
          │
          ▼
Transit Parameter Estimation
          │
          ▼
Feature Extraction
          │
          ▼
Machine Learning Classification
          │
          ▼
Exoplanet Detection Result
```

---

## 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Dataset | NASA TESS xCTL |
| Data Source | MAST Archive |
| Astronomy Library | Lightkurve |
| Data Processing | NumPy, Pandas |
| Machine Learning | Scikit-learn |
| Scientific Computing | SciPy |
| Visualization | Matplotlib |

---

## 📂 Repository Structure

```text
AI-Exoplanet-Detection/
│
├── tess_pipeline.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Output

The pipeline provides the following outputs:

- Best Transit Period
- Transit Depth
- Transit Duration
- Transit Mid-Time (T0)
- Signal-to-Noise Ratio (SNR)
- Folded Light Curve Visualization
- Machine Learning Prediction

---

## 🚀 Future Scope

- Deep Learning-based Transit Detection
- Multi-Planet Detection
- Real-time TESS Data Analysis
- Interactive Web Dashboard
- Automated Candidate Ranking

---

## 👨‍🚀 Team

### Team ANTARIKSH MITRA

Developed by **Team ANTARIKSH MITRA** as part of the **Bharatiya Antariksh Hackathon (BAH) 2026**.

---

## 📜 License

This project is intended for educational, research, and hackathon purposes.

---

## 🙏 Acknowledgements

- NASA TESS Mission
- MAST Archive
- Lightkurve
- Astropy
- Scikit-learn