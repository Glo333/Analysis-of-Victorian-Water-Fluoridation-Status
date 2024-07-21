# Analysis of Victorian Water Fluoridation Status

This project focuses on analyzing the fluoridation status of water companies in Victoria, Australia. The goal is to understand the patterns and associations in the data and to perform clustering to group similar water companies.

## Project Overview

### Objective

The objective of this project is to:
1. Analyze the dataset to understand the fluoridation status of water companies.
2. Perform clustering to identify groups of similar water companies based on the available features.
3. Compare different clustering methods and report their performance.

### Dataset

- **File Name**: FluoridationData.csv
- **Description**: The dataset contains 7 features related to the fluoridation status of different water companies. It includes various data types such as boolean, float, and string.
- **Source**: [Victorian Water Fluoridation Status by Postcode](https://discover.data.vic.gov.au/dataset/victorian-water-fluoridation-status-by-postcode)

## Instructions Followed

### Data Exploration

1. **Load the Data**: Load the data from the supplied file and print the data dimensions.
2. **Display Data Types**: Display the data types of all features. Print the median values for float features.
3. **Analyze Fluoride Levels**: Print all possible values of the "fluoride_level" feature and calculate the ratio of each value.
4. **Association Analysis**: Analyze the association between "melbourne" and "fluoride_level" and explain the results.
5. **Suburb Analysis**: Print the number of water companies in different suburbs and report any patterns.
6. **Largest Number of Water Companies**: Identify the suburb with the largest number of water companies.
7. **Largest Number of Fluoridated Companies**: Identify the suburb with the largest number of fluoridated companies.
8. **Data Frame Creation**: Create a data frame showing the number of water companies at different fluoride levels for different suburbs.
9. **Histogram**: Draw a histogram of the top 10 suburbs by the number of fluoridated companies and explain the results.

### Clustering

10. **Clustering Analysis**: Perform clustering on all water companies to determine the number of clusters. Compare this to the number of suburbs in the dataset.
11. **K-Means Clustering**: Choose the best K and perform K-Means clustering. Report the purity score.
12. **K-Means++ Clustering**: Perform K-Means++ clustering and report the purity score. Compare the results with K-Means clustering.
13. **Alternative Clustering Method**: Apply another clustering method and compare the results with K-Means and K-Means++.

## Results

The Jupyter notebook containing the code and outputs, as well as the report summarizing the findings, are presented in this repository.

## Technologies Used

- `Python`
- `Jupyter Notebook`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Installation

To run the analysis, you need to have Python and the necessary libraries installed. You can install the required libraries using the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn
