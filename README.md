# Fitness Tracker – Exercise Classification Using Wearable Sensor Data

## Project Overview
This project implements a **fitness tracker data science pipeline** that processes, visualizes, and models wearable sensor data to **classify strength training exercises**.

The system uses **accelerometer and gyroscope data** collected in real time to recognize different gym exercises. The end goal is to build a reliable **machine learning model** that can automatically identify exercises based on motion patterns.

---

## Exercises Classified
- Bench Press  
- Deadlift  
- Overhead Press  
- Barbell Row  
- Squat  

---

## Objective
The main objectives of this project are:
- To process raw wearable sensor data
- To visualize accelerometer and gyroscope signals for different exercises
- To engineer meaningful features from time-series data
- To train and evaluate multiple machine learning models
- To identify the best-performing model for exercise classification

---

## Dataset Description
- **Device Used:** MetaMotion wearable sensor  
- **Sensors:** Accelerometer & Gyroscope  
- **Data Collection:** Real-time  
- **Participants:** 5 individuals  
- **Data Type:** Multivariate time-series data  

The dataset captures realistic variations in movement caused by differences in users, lifting techniques, and execution speed, making the classification task more challenging and closer to real-world conditions.

---

## Project Workflow

###  Data Processing
- Cleaning raw accelerometer and gyroscope signals  
- Handling missing values and inconsistent sampling  
- Structuring data for analysis and modeling  

### Outlier Detection
- Detecting abnormal sensor spikes  
- Reducing noise caused by sensor drift and motion artifacts  

### Visualization
- Time-series visualization of sensor signals  
- Comparing movement patterns across exercises  
- Understanding biomechanical differences between lifts  

### Repetition & Distribution Analysis
- Analyzing exercise distribution  
- Checking repetition consistency across participants  

### Feature Engineering
- Extracting statistical features from sensor data  
- Scaling and transforming features for machine learning  

### Model Training & Evaluation
- Trained and evaluated multiple machine learning models  
- Compared model performance using classification metrics  
- **Random Forest achieved the highest accuracy** among all tested models  

---

## Tech Stack
- **Python**
- **Pandas & NumPy** – Sensor data processing
- **Matplotlib / Seaborn** – Data visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook** – Experimentation and analysis


