# Data Mining for Cardiovascular Disease Analysis

## Overview
This project aims to analyze cardiovascular disease (CVD) data using various data mining techniques. By exploring demographic, health, and lifestyle variables, we aim to contribute to the understanding of CVDs and aid in the development of preventive strategies and clinical interventions.

## Dataset
The dataset used for this analysis contains comprehensive information about individuals, including demographic details, health metrics, and lifestyle factors. Key variables include:
- **Age**: Age of individuals in years.
- **Gender**: Gender of individuals (0 for female, 1 for male).
- **Height**: Height of individuals in centimeters.
- **Weight**: Weight of individuals in kilograms.
- **Blood Pressure**: Systolic and diastolic blood pressure readings.
- **Cholesterol Levels**: Cholesterol levels (Above normal, Well above normal).
- **Glucose Levels**: Glucose levels (Above normal, Well above normal).
- **Smoking Habits**: Indicates smoking status (0 for No, 1 for Yes).
- **Alcohol Consumption**: Indicates alcohol consumption status (0 for No, 1 for Yes).
- **Physical Activity**: Indicates physical activity status (0 for No, 1 for Yes).

The dataset is available on Kaggle: [Cardiovascular Diseases Analysis](https://www.kaggle.com/code/ntltam/cardiovascular-diseases-analysis-w-data-mining/input).

## Data Cleaning
Data cleaning was performed to ensure data quality:
- Handling missing values.
- Transforming variables (e.g., converting age to years, binary encoding of gender).
- Calculating Body Mass Index (BMI).
- Validating blood pressure readings.
- Removing outliers to maintain data integrity.

## Data Transformation
Key transformations included:
- Converting age from days to years.
- Binary encoding of gender.
- BMI calculation using height and weight.
- Ensuring plausible blood pressure readings (AP_HI > AP_LO).

## Visualization
Graphical representations were used to understand variable distributions and relationships:
- Gender Distribution
- Cholesterol Levels
- Glucose Levels

## Clustering Analysis
Several clustering algorithms were applied to identify patterns and group similar data points:
1. **K-means Clustering**
   - Partition-based clustering to segment data into distinct clusters.
2. **Hierarchical Clustering**
   - Creating a tree-like structure of clusters.
3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
   - Identifying clusters based on density thresholds.
4. **Gaussian Mixture Models (GMM)**
   - Modeling the underlying probability distribution using Gaussian distributions.

## Performance Evaluation
The performance of each clustering algorithm was evaluated using metrics such as:
- Training accuracy
- Entropy
- Adjusted Rand index
- Silhouette coefficient
- Calinski Harabasz score

## Insights and Conclusions
The analysis revealed distinct subgroups within the dataset, providing insights into potential risk factors and health profiles associated with cardiovascular diseases. Key findings include:
- K-means has the highest training accuracy.
- Dendrogram (Complete) performs best in entropy, while K-means (Random) excels in adjusted rand index.
- Dendrogram (Complete) also scores highest in silhouette score, whereas K-means (K-means++) is best for Calinski Harabasz score.

For more details, read the [Medium article](https://medium.com/@krashwin192002/unveiling-insights-data-mining-for-cardiovascular-disease-analysis-ee148d5348aa).

## Author
**Ashwin K R** 
