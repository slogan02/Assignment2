# Assignment 2: Engineering Predictive Features

## Overview

This repository contains starter code for practicing feature engineering with the Ames Housing dataset. You'll create new predictive features, train models, and measure the impact of feature engineering on model performance.

## Repository Structure

```
├── data/
│   └── train.csv              # Ames Housing dataset (download required)
├── starter_code.ipynb         # Main working file - complete this
├── README.md                  # This file
```

## Setup

### 1. Install Required Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 2. Explore the Dataset

The [Ames Housing Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) has been included in the `/data` directory.

Explore `data_description.txt` to understand the shape of the data that is in the file. Additionally, there is a `train.csv` file with training data and a `test.csv` file with testing data.

### 3. Run the Notebook

**Using Jupyter Notebook:**
```bash
jupyter notebook starter_code.ipynb
```

**Using VS Code:**
Open `starter_code.ipynb` in VS Code with the Jupyter extension installed.

## What You'll Build

- Baseline Random Forest model using raw features
- 5+ engineered features based on real estate domain knowledge
- Comparison showing how feature engineering improves predictions
- Analysis of which features provide the most value

## Submission

Once complete, push your work to GitHub:

```bash
git add .
git commit -m 'completed feature engineering assignment'
git push
```

Submit your GitHub repository link on the course platform.

## Dataset Information

**Ames Housing Dataset:**
- 1,460 houses with 79 features
- Target variable: `SalePrice` (home sale price)
- Features include: square footage, quality ratings, age, location, amenities, and more
- Full documentation: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data