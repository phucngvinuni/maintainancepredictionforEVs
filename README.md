

```markdown
# Maintenance Prediction for Electric Vehicles (EVs)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview
As Electric Vehicles (EVs) continue to dominate the automotive industry, maintaining their reliability and performance is paramount. This repository presents a **Machine Learning (ML)-driven Predictive Maintenance System** tailored for EVs. By leveraging real-time sensor data, the system predicts potential faults, reducing unexpected failures, optimizing repair schedules, and extending the lifespan of critical EV components.

## Key Features
- **Data Enhancements:**
  - Outlier detection and removal using DBSCAN.
  - Balanced dataset for better model performance.
- **Model Improvements:**
  - Implemented **LightGBM** for efficient and accurate predictions.
  - Achieved an **accuracy of 65%** with the current setup.
- **Real-World Applicability:**
  - Uses features like engine RPM, lubrication oil pressure, fuel pressure, coolant pressure, lubrication oil temperature, coolant temperature, and engine condition.
  - Suitable for edge deployment in EVs for real-time maintenance insights.

## Inspiration and Original Data
This project was inspired by and extends the work from:
[ML-Based Vehicle Predictive Maintenance System with Real-Time Visualization](https://github.com/iDharshan/ML-Based-Vehicle-Predictive-Maintenance-System-with-Real-Time-Visualization/tree/main).

## Why Predictive Maintenance for EVs?
Traditional EV maintenance approaches—either fixed-schedule or reactive—often lead to unexpected failures and costly repairs. Our predictive maintenance system:
- Monitors **real-time sensor data**.
- **Predicts potential faults** before they occur.
- Reduces **downtime** and **maintenance costs**.
- Enhances **vehicle safety** and **user experience**.
- Supports sustainability by extending the life of EV components.

## Features and Dataset
The model processes data with features including:
- **Engine RPM**
- **Lubrication Oil Pressure**
- **Fuel Pressure**
- **Coolant Pressure**
- **Lubrication Oil Temperature**
- **Coolant Temperature**
- **Engine Condition (target)**

Advanced data preprocessing ensures a clean and balanced dataset for training and evaluation.

## Model Performance
The system uses **LightGBM** for predictive modeling, achieving an accuracy of **65%** on the test data. Future improvements are aimed at increasing this metric through advanced feature engineering and model tuning.

## Getting Started
### Prerequisites
- Python 3.8+
- Key Python libraries: `lightgbm`, `pandas`, `numpy`, `scikit-learn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/maintainancepredictionforEVs.git
   cd maintainancepredictionforEVs
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Preprocess the dataset:
   ```bash
   python preprocess.py
   ```
2. Train the model:
   ```bash
   python train.py
   ```
3. Evaluate the model:
   ```bash
   python evaluate.py
   ```

### Future Improvements
- Integrate additional sensor data for better predictions.
- Improve accuracy through ensemble learning and hyperparameter optimization.
- Develop a user-friendly dashboard for visualization and real-time fault alerts.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## Acknowledgments
Thanks to [iDharshan](https://github.com/iDharshan) for providing the original dataset and project inspiration.
```
