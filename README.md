# Titanic Survival Prediction

## Overview

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the "unsinkable" RMS Titanic sank after colliding with an iceberg, leading to the deaths of 1502 out of 2224 passengers and crew. While some aspects of survival were due to chance, certain groups of people were more likely to survive than others. 

This project aims to build a predictive model to answer the question: **"What sorts of people were more likely to survive?"** using passenger data such as name, age, gender, socio-economic class, and other relevant features.

## Project Structure

```bash
Titanic-Survival-Prediction/
│
├── data/
│   ├── train.csv              # Training dataset
│   ├── test.csv               # Test dataset
│   └── ...
│
├── notebooks/
│               
│   └── Modeling.ipynb         # Model building and evaluation
│
├── src/
│   ├── data_preprocessing.py  # Data cleaning and preprocessing scripts
│   ├── feature_engineering.py # Feature engineering scripts
│   ├── model.py               # Model training and prediction scripts
