# Machine Learning-Based Predictive Maintenance System for an Electric Motor

## 📌 Project Overview

This project focuses on the development of a **machine learning-based predictive maintenance system for an electric motor**.

The system will analyze motor operating parameters such as **temperature, vibration, current, rotational speed, and load** to identify abnormal operating conditions and predict potential motor faults.

The project combines **Mechatronics Engineering, Python programming, data analysis, and machine learning** to demonstrate how data-driven techniques can be applied to the monitoring and maintenance of electromechanical systems.

This project is being developed as part of my **Industrial Training (IT/SIWES)** and serves as a practical demonstration of the programming, data analysis, and machine learning skills acquired during the training.

---

## 🎯 Objectives

The main objectives of this project are to:

- Develop and organize a dataset representing electric motor operating conditions.
- Use Python to process and analyze motor operating data.
- Apply NumPy for numerical computations.
- Use Pandas for data manipulation and analysis.
- Use Matplotlib to visualize motor operating parameters.
- Perform exploratory data analysis to identify patterns and relationships within the data.
- Prepare the dataset for machine learning.
- Train and compare machine learning classification models.
- Evaluate the performance of the trained models.
- Develop a system capable of predicting whether a motor is operating normally or under a faulty condition.
- Demonstrate the potential application of machine learning in predictive maintenance.

---

## ⚙️ Project Concept

The general workflow of the system is:

```text
Motor Operating Data
        ↓
Data Collection / Generation
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Feature Selection
        ↓
Machine Learning
        ↓
Model Evaluation
        ↓
Motor Condition Prediction
        ↓
Normal / Fault
```

---

## 📊 Motor Parameters

The project will initially consider parameters such as:

| Parameter       | Description                               |
| --------------- | ----------------------------------------- |
| Temperature     | Motor operating temperature               |
| Vibration       | Motor vibration level                     |
| Current         | Electrical current drawn by the motor     |
| Speed           | Motor rotational speed                    |
| Load            | Operating load on the motor               |
| Operating Hours | Duration of motor operation               |
| Condition       | Target variable representing motor health |

The exact parameters and dataset structure may be modified as the project develops.

---

## 🛠️ Technologies and Tools

### Programming

- **Python**

### Data Analysis

- **NumPy**
- **Pandas**
- **Matplotlib**

### Machine Learning

- **Scikit-learn**

### Development Environment

- **Jupyter Notebook**
- **Visual Studio Code**

### Version Control

- **Git**
- **GitHub**

Additional tools may be introduced as the project progresses.

---

## 📁 Project Structure

```text
Machine-Learning-Predictive-Maintenance/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── models/
│
├── visualizations/
│
└── documentation/
```

### Directory Description

**`data/`**
Contains the datasets used by the project.

- `raw/` — Original or unprocessed datasets.
- `processed/` — Cleaned and prepared datasets.

**`notebooks/`**
Contains Jupyter Notebooks used for learning, experimentation, data analysis and machine-learning development.

**`src/`**
Contains reusable Python source code used by the project.

**`models/`**
Contains trained machine-learning models.

**`visualizations/`**
Contains graphs and other visual outputs generated during the analysis.

**`documentation/`**
Contains project documentation, reports and supporting materials.

---

## 🔬 Development Stages

The project will be developed progressively through the following stages:

### 1. Python Programming

Development of the Python programming skills required for data processing and automation.

### 2. Numerical Computing

Application of NumPy to perform numerical operations on motor-related data.

### 3. Data Analysis

Use of Pandas to load, clean, organize and analyze motor datasets.

### 4. Data Visualization

Use of Matplotlib to visualize motor operating parameters and identify trends and relationships.

### 5. Dataset Development

Creation or acquisition of a dataset representing different motor operating conditions.

### 6. Exploratory Data Analysis

Investigation of relationships between motor parameters and operating conditions.

### 7. Machine Learning

Training classification models to distinguish between normal and abnormal motor conditions.

### 8. Model Evaluation

Evaluation and comparison of machine-learning models using appropriate performance metrics.

### 9. Predictive Maintenance System

Integration of the data-processing and machine-learning components into a functional prediction workflow.

### 10. Testing and Documentation

Testing the system, documenting the results and preparing the final project presentation.

---

## 📈 Expected Outcome

The final system is expected to accept motor operating parameters as input and use a trained machine-learning model to predict the motor's operating condition.

For example:

```text
Temperature: 68 °C
Vibration:   0.82
Current:     4.8 A
Speed:       1400 RPM
Load:        80%

             ↓

       Machine Learning Model

             ↓

       ⚠ FAULT DETECTED
```

The final model and its performance will depend on the quality and characteristics of the dataset used during development.

---

## ⚠️ Project Limitations

The initial version of the project may use **simulated or publicly available motor data** rather than measurements obtained from a physical electric motor.

Therefore, the results may not completely represent the behavior of every real-world motor.

Future development could involve collecting real-time data from physical sensors connected to an electric motor.

---

## 🚀 Future Improvements

Possible future improvements include:

- Integration with real motor sensors.
- Real-time data acquisition.
- Temperature, vibration and current sensors.
- Microcontroller-based data collection.
- Real-time motor-condition monitoring.
- IoT connectivity.
- Development of a monitoring dashboard.
- Detection of multiple specific motor fault types.
- Deep learning models.
- Deployment of the trained model to an edge device.

---

## 👨‍💻 Project Context

This project is being developed as part of my **Industrial Training (IT/SIWES)** as a **Mechatronics Engineering student**.

It demonstrates the application of programming, data analysis and machine learning techniques to an engineering problem involving the monitoring and maintenance of electromechanical systems.

---

## 📌 Project Status

**Status:** 🚧 In Development

The project is being developed progressively as new programming, data analysis and machine-learning concepts are learned and applied.
