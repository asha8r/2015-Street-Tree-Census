# 2015-Street-Tree-Census
Analysis of "2015 Street Tree Census" dataset.

## Description
This work analyzes the 2015 Street Tree Census data to uncover insights into New York City's urban tree population, focusing on tree health, species distribution, and environmental factors.

## Technologies and Packages Used
- Python: Primary programming language.  
- Pandas: For data manipulation and analysis. 
- NumPy: For numerical computing.
- Matplotlib: For creating static and interactive visualizations.
- Seaborn: For high-level data visualization.
- SciPy: For scientific computing and technical mathematics.

## Installation and Setup
To execute this analysis, utilize any web-based platforms that support Python, such as Google Colab or Jupyter Notebook, or you can run it on offline platforms that are compatible with Python.

# code to install the packages
pip install pandas numpy matplotlib seaborn scipy

## Use the Below code to import the libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import chi2_contingency, pearsonr, f_oneway

## Load the Dataset
First download the dataset from the GitHub repository, which is in the form of zip file, extract it and save it.
NOTE: if you are using Colob save it in the drive, The same things applies to all the platforms.

## Key Components of the Analysis

### Data Cleaning
- Removes missing values and filters relevant columns, preparing the dataset for analysis.

### Descriptive Statistics
- Provides basic statistical descriptions like mean, median, and mode of the dataset's key features.

### Data Visualization
- Generates various plots such as histograms, bar charts, and scatter plots for visual data interpretation.

### Hypothesis Testing
- Performs statistical tests like Chi-Square, Pearson correlation, and ANOVA to understand relationships within the data.

### Temporal Analysis
- Analyzes trends over time in tree characteristics like health, diameter, and species diversity.

### Outlier Detection
- Identifies and handles outliers in the dataset, particularly in tree diameter data.









