# Density-Based Clustering using DBSCAN on the Iris Dataset

## Project Overview

This project demonstrates the use of the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm on the Iris dataset. The objective is to identify natural groupings of observations and detect potential outliers without specifying the number of clusters in advance.

## Why DBSCAN?

DBSCAN is a density-based clustering algorithm that:
- Does not require the number of clusters beforehand.
- Can identify clusters of arbitrary shapes.
- Detects noise and outlier points automatically.

## Dataset

The project uses the Iris dataset available through scikit-learn.

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

1. Load the Iris dataset.
2. Perform exploratory data analysis.
3. Standardize features.
4. Apply DBSCAN clustering.
5. Visualize clusters.
6. Analyze clustering results.

## Results

DBSCAN successfully grouped similar observations based on feature density and identified potential outliers.

## Installation

```bash
pip install -r requirements.txt