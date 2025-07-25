# Assignment 5 – Machine Learning in R

This repository contains a Jupyter notebook that walks through a complete machine learning workflow using the Iris dataset and the `caret` package in R. The project is adapted from Jason Brownlee’s R tutorial and is designed to help beginners practice classification modeling, algorithm comparison, and data partitioning in R.

---

## Table of Contents

- [Project Description] 
- [Installation Instructions] 
- [Usage]  
- [Project Structure]  
- [License]  
- [Acknowledgments]  

---

## Project Description

This notebook demonstrates the process of building classification models using R, focusing on:

- Data loading and splitting using `caret::createDataPartition`
- Algorithm comparison using resampling and cross-validation
- Model selection and prediction evaluation
- Visualization of classification performance

The project is aimed at students and early learners who want hands-on experience with supervised machine learning workflows in R.

---

## Installation Instructions

### Clone the Repository

```bash
git clone https://github.com/Greezxy/Assignment5-MachineLearning-in-R.git
cd Assignment5-MachineLearning-in-R
```

### Create and Activate the Conda Environment
```bash
conda env create -f environment-assignment5-r.yml
conda activate iris-ml-r
```  
This will install R 4.2 and core packages used in the notebook including:  
- caret, ggplot2, e1071, randomForest, tidyverse, and jupyterlab with R kernel support.

## Usage
To launch the R notebook:
```bash
jupyter lab
```

Then open the file:
Machine Learning in R.ipynb

The notebook walks through:  
- Loading and splitting the Iris dataset
- Comparing multiple classification models
- Measuring accuracy and performance metrics
- Visualizing results using featurePlot() and base R plots

All results are fully reproducible with the provided environment and dataset.

## Project Structure
Assignment5-MachineLearning-in-R/  
├── Machine Learning in R.ipynb       # Jupyter notebook with full ML workflow in R  
├── environment-assignment5-r.yml     # Conda environment for R notebook
├── iris.csv                          # Iris dataset used for training and evaluation  
└── README.md                         # Project overview and setup instructions

## License
This project is for educational use only and is part of a course assignment.

## Acknowledgments
Based on the tutorial by Jason Brownlee:  
Machine Learning in R Step-by-Step  
© Jason Brownlee, MachineLearningMastery.com

---
