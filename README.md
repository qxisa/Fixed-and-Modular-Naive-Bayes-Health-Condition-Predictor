# Fixed-and-Modular-Naive-Bayes-Health-Condition-Predictor
This project implements a Health Condition Predictor that forecasts diseases based on patient symptoms using machine learning classification algorithms, specifically the Naive Bayes approach. The system leverages a real-world medical dataset containing diseases and their associated symptoms to build a predictive model.

# Health Condition Predictor (Naive Bayes)

## Project Overview
The Health Condition Predictor is a machine learning-based application that predicts diseases from user-provided symptoms. This project implements a Naive Bayes classifier trained on a curated dataset of diseases and their symptoms. Additionally, it enriches predictions with symptom severity information, disease descriptions, and precautionary measures.

## Features
- Disease prediction based on symptoms using Naive Bayes classification
- Utilizes multiple datasets including symptom severity and disease precautions
- Outputs detailed information on the predicted disease:
  - Disease description
  - Recommended precautions
  - Symptom severity scores

## Dataset
The model is trained on a medical dataset containing:
- Disease names and their associated symptoms
- Symptom severity weights
- Disease precaution measures
- Disease and symptom descriptions

## Requirements
- Python 3.x
- pandas
- scikit-learn

Optional (for future neural network implementation):
- tensorflow or keras

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/health-condition-predictor.git
   cd health-condition-predictor

   ├── dataset.csv
├── Symptom-severity.csv
├── symptom_precaution.csv
├── Disease precaution.csv
├── symptom_description.csv
├── HealthConditionPredictor.ipynb
└── README.md


Future Work
Implement a neural network-based prediction model

Build a graphical user interface (GUI) for easier interaction

Expand dataset to include more diseases and symptoms

Integrate real-time symptom input and advice generation
