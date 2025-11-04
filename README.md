# Human Action Detection using Motion Sensor Data

> **This project focuses on building a machine learning pipeline to detect and classify human actions based on time-series motion or sensor data, such as accelerometer or gyroscope readings. Such a system has practical applications in health monitoring, activity recognition, fitness tracking, and gesture-based control systems.**

**The notebook walks through preprocessing, feature engineering, model training, and evaluation using popular ML techniques**

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Data Sources](#data-sources)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results & Evaluation](#results--evaluation)
- [Requirements](#requirements)


---

## Overview

This repository provides a complete workflow for predicting and analyzing human actions from motion or sensor datasets using machine learning algorithms. The project is implemented entirely in Python Jupyter Notebooks for transparency and reusability.

---

## Features

- **End-to-End Pipeline:** Data loading, preprocessing, feature engineering, model training, evaluation, and prediction.
- **Supervised Learning:** Implements classifiers such as Random Forest, SVM, and more.
- **Sensor Data Analysis:** Handles motion/sensor CSV datasets, visualizes signals, and explores statistical properties.
- **Model Performance Evaluation:** Plots confusion matrix, accuracy, precision, recall, and F1-score.
- **Google Colab Ready:** Easy to run in Colab or Jupyter.

---

## Project Structure

```
Human-Action-Detection/
│
├── Human_Action_Detection.ipynb   # Main Jupyter Notebook for the entire ML workflow
├── data/                         # Raw and processed sensor/motion data
│   └── sensor_data.csv
├── models/                       # Saved model files (.pkl or .joblib)
├── images/                       # Plots/figures from analysis
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
```

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AnanyaGubba/Human-Action-Detection.git
   ```

2. **Run on Google Colab or Jupyter:**
   - Open `Human_Action_Detection.ipynb` in your Colab or local Jupyter environment.

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Prepare the dataset:**
   - Place your sensor or motion data file in the `data/` folder and update the notebook path if needed.

---

## Data Sources

- Public datasets (links or references provided in the notebook)
- Typical data format: CSV files with time series sensor/motion readings and labeled actions

---

## Usage

- **Notebook:** Run notebook cells in order for data processing, training, and evaluation.
- **Custom Data:** Replace `sensor_data.csv` with your own motion/sensor data.
- **Model Saving/Loading:** Code included for saving and reusing trained models.

---

## Model Details

- **Algorithms:** Random Forest, Support Vector Machine (SVM), Logistic Regression, etc.
- **Feature Engineering:** Time-domain and frequency-domain features, normalization.
- **Training:** Train/Test split, cross-validation, hyperparameter tuning.
- **Evaluation:** Visualization of results, metrics calculation.

---

## Results & Evaluation

- Confusion matrix, classification report, accuracy plots
- Example result summaries and best model selection
- Key insights noted in the notebook documentation

---

## Requirements

The required Python packages are listed in [`requirements.txt`](requirements.txt).  
To install them, run:

```bash
pip install -r requirements.txt
```

Typical dependencies include:
```bash
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- joblib
```

Please see the [`requirements.txt`](requirements.txt) file for the complete list and versions.

