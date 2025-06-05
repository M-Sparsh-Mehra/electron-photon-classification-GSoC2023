# electron-photon-classification-GSoC2023
This repository contains my solution to the Electron vs. Photon Classification task for GSoC 2023. 

## 📊 Task Overview

The objective is to classify particles (electrons vs. photons) using sparse calorimeter data. The dataset contains **32×32 pixel images** with two channels:
- **Energy deposition**
- **Hit timing**

The goal is to design a deep learning model that achieves an **ROC AUC score ≥ 0.80** using both:
-  **CNN**
-  **Other simpler models**

 ## 📁 Dataset

Datasets taken from CERNBox:
- 📎 [Photon Data](https://cernbox.cern.ch/index.php/s/AtBT8y4MiQYFcgc)
- 📎 [Electron Data](https://cernbox.cern.ch/index.php/s/FbXw3V4XNyYB3oA)

## 📓 Notebooks

- `particle classification lgbm.ipynb` — Logistic and LightGBM training and evaluation
- `particle classification cnn final.ipynb` — CNN-based training and evaluation


## 📈 Results

| MODEL              | ROC AUC Score  |
|--------------------|----------------|
| Light GBM          | *0.778*        |
| Logistic Regression| *0.656*        |
| CNN                | *0.801*        |


## Authors

**M Sparsh Mehra**  
GitHub: https://github.com/M-Sparsh-Mehra

**Dheeraj Pant**    

We worked together on this implementation.
  
