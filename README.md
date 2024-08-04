# Exploratory Data Analysis (EDA) of Iris Dataset

## Description
This project performs exploratory data analysis on the Iris dataset using various statistical and visualization techniques. It includes histograms, box plots, and calculation of interquartile ranges (IQR) for outlier detection.

## Files
- `iris_eda.ipynb`: Jupyter Notebook containing the code and results for the exploratory data analysis of the Iris dataset.

## Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib

## Usage
1. Clone the repository.
2. Open the Jupyter Notebook `iris_eda.ipynb`.
3. Run the cells to see the exploratory data analysis of the Iris dataset.

## Code Overview
1. **Data Import**:
    - Load the Iris dataset from seaborn's repository.

2. **Data Exploration**:
    - Display the first few rows of the dataset.
    - Identify unique species in the dataset.
    - Display dataset information and summary statistics.

3. **Visualizations**:
    - Create histograms for each feature.
    - Create box plots for numeric columns to identify outliers.

4. **Outlier Detection**:
    - Calculate the interquartile range (IQR) for 'sepal_length'.
    - Determine the upper and lower bounds for outliers.

## Results
- The results include histograms and box plots for each feature and the calculation of IQR for 'sepal_length'.
