# Ai-ML-Tasks
# TASK - Iris Dataset Exploration and Visualization

## Overview

This project demonstrates basic **data analysis** and **data visualization** techniques using the famous **Iris Dataset**. The notebook explores how to load data, inspect its structure, generate summary statistics, and visualize feature relationships using **Pandas**, **Matplotlib**, and **Seaborn**.

This task is designed to build foundational skills in exploratory data analysis (EDA).

## Objective

* Load and inspect a dataset.
* Understand data structure and feature distributions.
* Identify trends, relationships, and possible outliers.
* Practice visualization using Python libraries.

## Dataset

The project uses the **Iris Dataset**, which contains measurements of iris flowers from three species:

* Setosa
* Versicolor
* Virginica

Features included:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Files

* `TASK_1.ipynb` → Main notebook containing code and visualizations.
* `Task-1.docx` → Task instructions and objectives.
* `iris.csv` → Dataset exported during notebook execution.

## Workflow

### 1. Import Libraries

Required libraries are imported for data handling and visualization.

### 2. Load Dataset

The Iris dataset is loaded using Seaborn and also saved as a CSV file.

### 3. Data Inspection

The notebook checks:

* Dataset shape
* Column names
* First few rows using `.head()`
* Data types using `.info()`
* Statistical summary using `.describe()`

### 4. Data Visualization

#### Using Seaborn

* Pairplot / Scatter Plot
* Histograms
* Box Plots

#### Using Matplotlib

* Scatter plots between features
* Histograms for distributions
* Box plots for outlier detection

## Key Learning Outcomes

* Data loading with Pandas
* Dataset inspection and summary statistics
* Feature comparison using scatter plots
* Distribution analysis using histograms
* Outlier detection using box plots
* Practical use of Matplotlib and Seaborn

## How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run `TASK_1.ipynb`

## Sample Visualizations

The notebook generates multiple charts to better understand the dataset, including pairplots, histograms, and boxplots.

## Author

USAMA TARIQ
