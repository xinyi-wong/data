# 📊Datathon

# 👩‍🔬Fetal Distress Prediction using Cardiotocography Data 

This repository contains the code and resources for the **2025 Datathon** competition, where the goal was to predict fetal distress in expectant mothers using cardiotocography (CTG) data. The model classifies the CTG data into three categories: **Normal**, **Suspect**, and **Pathologic** to assist healthcare professionals in timely decision-making during labor.

## 📍Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)


## 📎Project Overview:
This project focuses on using machine learning to analyze CTG (Fetal Heart Rate and Uterine Contractions) data to predict the fetal state. The main challenge is to build a reliable model that can distinguish between three categories of fetal health:
- **Normal**: No immediate concern.
- **Suspect**: Warning signs present, requiring monitoring.
- **Pathologic**: High risk of distress, requiring urgent attention.
The dataset used is the **UCI Cardiotocography dataset**, which includes real-world data from over 2,000 CTG traces labeled by obstetricians.

## 📑Dataset

The dataset used for this project is the **UCI Cardiotocography dataset**, which contains 2,000+ CTG traces recorded from expectant mothers. The dataset includes features such as:

- **LB (Baseline Heart Rate)**: The resting heart rate of the fetus.
- **AC (Accelerations)**: Short bursts of increased heart rate.
- **FM (Fetal Movements)**: The movements of the fetus.
- **UC (Uterine Contractions)**: The tightening of the uterus during labor.
- **DL, DS, DP (Decelerations)**: Sudden drops in the heart rate.
- **ASTV, ALTV (Short-Term and Long-Term Variability)**: Measures of heart rate variability.

For more details on the dataset, visit: [UCI Cardiotocography Dataset](https://archive.ics.uci.edu/dataset/193/cardiotocography).

## 🔑Installation

To get started, clone the repository:

```bash
git clone https://github.com/xinyi-wong/data.git
```
Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 💊Models

The following machine learning models were implemented for the classification task:

- Logistic Regression

- Random Forest

- Gradient Boosting

- SVC
  
- SMOTE


## 🩺Evaluation Metrics


- Balanced Accuracy: Ensures that all classes are treated fairly.

- Macro F1-Score: Balances precision and recall across all classes.

## 📒Results

The results show that the model is reliable in detecting pathologic cases of fetal distress.
