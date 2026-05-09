# EDA-implementation-on-diabetes-dataset
Comprehensive EDA on Diabetes Dataset featuring statistical summaries and visualizations for all medical predictor variables.

# Diabetes Dataset - Exploratory Data Analysis (EDA)

## Overview
This project performs a thorough Exploratory Data Analysis (EDA) on the Pima Indians Diabetes Dataset. The analysis provides statistical summaries and visual distributions for all medical features used in diabetes prediction.

Dataset is available as one of project files.

## Dataset Columns
| Column | Description |
|--------|-------------|
| **Pregnancies** | Number of times pregnant |
| **Glucose** | Plasma glucose concentration (oral glucose tolerance test) |
| **BloodPressure** | Diastolic blood pressure (mm Hg) |
| **SkinThickness** | Triceps skin fold thickness (mm) |
| **Insulin** | 2-Hour serum insulin (mu U/ml) |
| **BMI** | Body mass index (weight in kg/(height in m)²) |
| **DPF** | Diabetes pedigree function (genetic risk factor) |
| **Age** | Age in years |
| **Outcome** | Target variable (0 = No Diabetes, 1 = Diabetes) |

## Analysis Performed

### 1. Statistical Summary for Every Column
For each of the 9 columns, the code calculates and displays:
- **Minimum** value
- **Maximum** value
- **Mean** (average)
- **Standard Deviation** (spread of data)
- **Missing Values** indicator (presence of nulls)

### 2. Visualizations (Performed on All Columns)
Each column receives three plots:
- **Histogram** – Shows data distribution and frequency
- **Boxplot** – Identifies outliers and shows median/IQR
- **Scatter Plot** – Reveals data clusters and patterns

### Example Visualization Output

Column: Glucose
Min: 0
Max: 199
Mean: 120.89
Standard Deviation: 31.97
Missing Values: 0


## Key Insights from This Analysis

| Column | Typical Range | Notes |
|--------|---------------|-------|
| Pregnancies | 0 - 17 | Most patients have 0-3 pregnancies |
| Glucose | 44 - 199 | Zero values may indicate missing data |
| BloodPressure | 24 - 122 | Zero values likely erroneous |
| BMI | 18.2 - 67.1 | Elevated BMI common in diabetes patients |
| Age | 21 - 81 | Diabetes risk increases with age |

## Requirements
```bash
pip install pandas numpy matplotlib seaborn

```

Run the .ipynb notebook in Jupyter/Colab; a detailed academic report covering the full project pipeline (model choice, visualization, preprocessing, results) is also included.
