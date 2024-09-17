# Data Visualization of Iris Dataset

## Project Overview
This project provides a comprehensive exploration and visualization of the Iris dataset using Python libraries, Matplotlib, and Seaborn. The Iris dataset is a well-known dataset in machine learning and statistics, consisting of measurements from three species of iris flowers: **Setosa**, **Versicolor**, and **Virginica**. The goal is to showcase various data visualization techniques to better understand the relationships between features within the dataset.

## Dataset
The Iris dataset consists of 150 samples, each containing the following four features:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

These features are measured across the three iris species.

## Visualizations
The following visualizations are implemented in the project:

- **Pair Plot**: Displays pairwise relationships between features using scatter plots and histograms, colored by species.
- **Pie Chart**: Illustrates the frequency of each iris species in the dataset.
- **Scatter Plot**: Shows the relationship between sepal length and sepal width, color-coded by species.
- **Feature Distribution**: Visualizes the distribution of sepal and petal features using histograms.
- **Joint Plot**: Combines scatter and marginal distributions for sepal length and sepal width.
- **KDE Plots (Kernel Density Estimation)**:
  - Visualizes the density of sepal features for the Setosa species.
  - Displays the density of petal features for the Setosa species.

## General Statistical Summary
The project also includes a summary of basic statistical measures (mean, standard deviation, minimum, maximum, etc.) for each feature, providing an overview of the dataset.

## Requirements
To run the project, you'll need:

- Python 3.x
- Libraries: 
  - Matplotlib
  - Seaborn
  - Pandas

Install the required libraries using the following command:

```bash
pip install matplotlib seaborn pandas
