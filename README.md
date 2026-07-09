# AI-Seizure-Prediction
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Random_Forest-orange)](https://scikit-learn.org/)
[![NeuroKit2](https://img.shields.io/badge/NeuroKit2-ECG_Processing-red)](https://neuropsychology.github.io/NeuroKit/)
[![MNE](https://img.shields.io/badge/MNE-Biosignal_Analysis-purple)](https://mne.tools/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-013243)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

--------
## DESCRIPTION

This repository contains the Artificial Intelligence (AI) module of the **Smart System for Early Prediction of Epileptic Seizures (EPIXA)**.
The AI system analyzes ECG signals acquired from a wearable device to predict epileptic seizures before onset. It combines biomedical signal processing, feature engineering, and personalized machine learning to identify seizure-related patterns from cardiac activity.
A personalized Random Forest classifier is trained for each patient to improve prediction performance. To further enhance reliability, ECG-based predictions are combined with motion information extracted from accelerometer (ACC) signals using a multimodal fusion strategy.

### AI Workflow

![AI Workflow](Images/WorkFlow.png)

--------

## 1) Preprocessing

Each recording undergoes signal preprocessing before feature extraction.
Processing steps include:
- Band-pass filtering
- Notch filtering
- cleaning
- Signal normalization
- Window segmentation



















## 🔗 Related Repositories

- [Project Overview](https://github.com/Reemwael720/Smart-System-for-Early-Prediction-of-Epileptic-Seizures-EPIXA-)

- [Wearable-Seizure-Detection-Hardware](https://github.com/Reemwael720/Wearable-Seizure-Detection-Hardware)

- [Seizure-Alert-Mobile-App](https://github.com/Reemwael720/Seizure-Alert-Mobile-App)
