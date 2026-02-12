# Task 1 - Iris Dataset Exploration and Visualization (EDA)

## Objective
The objective of this task is to explore and visualize the Iris dataset using Python libraries such as Pandas, Matplotlib, and Seaborn.  
This task focuses on understanding the dataset structure, feature distributions, and relationships between variables through Exploratory Data Analysis (EDA).

##  Dataset Used
Dataset Name: Iris Dataset  
Source: Seaborn Library (`sns.load_dataset("iris")`)  

The Iris dataset contains 150 samples of iris flowers with 4 numerical features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width  

And one categorical column:
- Species (setosa, versicolor, virginica)

##  Libraries Used
- pandas
- matplotlib
- seaborn

## Steps Performed

###  Loading the Dataset
The dataset was loaded using Seaborn and stored into a Pandas DataFrame.

###  Dataset Inspection
The dataset was inspected using:
- `.shape`
- `.columns`
- `.head()`

### Dataset Information
The dataset information was checked using:
- `.info()`

This step was used to confirm:
- data types
- missing values
- dataset structure

### Summary Statistics
Summary statistics were generated using:
- `.describe()`

This provided:
- mean
- standard deviation
- minimum/maximum values
- quartiles

### Missing Values Check
Missing values were checked using:
- `df.isnull().sum()`

### 6️Data Visualization
The dataset was visualized using:
- Scatter plots (relationship between features)
- Histograms (feature distribution)
- Box plots (outlier detection and feature spread)

# Outputs / Screenshots

## Dataset Preview (Head)
[Dataset Head](outputs/head.png)

## Dataset Information (info)
[Dataset Info](outputs/info.png)

## Summary Statistics (describe)
[Describe Output](outputs/describe.png)

## Missing Values Check
[Missing Values](outputs/missing_value.png)

# Scatter Plots

## Scatter Plot 1
[Scatter Plot 1](outputs/scatter_1.png)

## Scatter Plot 2
[Scatter Plot 2](outputs/scatter_2.png)

# Histogram

## Histogram of Features
[Histogram](outputs/histogram.png)

#  Box Plots

## Box Plot 1
[Box Plot 1](outputs/box_plot1.png)

## Box Plot 2
[Box Plot 2](outputs/box_plot2.png)

# Conclusion
- The Iris dataset contains 150 rows and 5 columns.
- There are no missing values in the dataset.
- Scatter plots show that petal length and petal width provide better separation among species.
- Histograms show the distribution of feature values across the dataset.
- Box plots highlight feature spread and help in detecting outliers.
