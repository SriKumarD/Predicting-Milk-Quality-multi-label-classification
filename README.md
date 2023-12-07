# Milk Quality Prediction (Classification)

## Introduction
This project leverages machine learning models to predict the quality of milk using a dataset manually collected from various observations in the dairy industry. The dataset includes critical factors influencing milk quality, providing a basis for predictive analysis.

## About the Dataset
- **Source**: [Milk Quality Dataset on Kaggle](https://www.kaggle.com/datasets/cpluzshrijayan/milkquality)
- **Features**: The dataset features 7 independent variables: pH, Temperature, Taste, Odor, Fat, Turbidity, and Color. These parameters are key to determining milk quality.
- **Target Variable**: The grade of milk, categorized into Low (Bad), Medium (Moderate), and High (Good).
- **Data Encoding**: Binary encoding for Taste, Odor, Fat, and Turbidity (1 for optimal conditions, 0 otherwise). Temperature and pH are recorded with actual values.

## Objective
The aim is to apply data preprocessing, data augmentation, and statistical as well as predictive models to assess milk quality. The project explores machine learning's potential in enhancing quality control in the dairy industry.

## Data Loading and Processing
The dataset, 'milknew.csv', is loaded for analysis. The data cleaning and preprocessing steps transform the dataset into a format suitable for machine learning models.

## Exploratory Data Analysis
The exploratory analysis includes statistical summaries, visualizations, and insights, providing a deeper understanding of the dataset's characteristics and the relationships between different variables.

## Model Building
Various models were used, including K-Nearest Neighbors (KNN), Decision Tree, AdaBoost, Random Forest, Gradient Boost, and XGBoost. Each model's configuration was carefully chosen to suit the nature of the dataset and the prediction objective.

## Results and Evaluation
- **Performance**: The models achieved high accuracy, with AdaBoost showing the lowest at 95.2%. This level of accuracy is critical for food-related predictions, particularly those with potential health impacts.
- **Accuracy as a Metric**: Given the significant implications of false positives and negatives, accuracy was the primary metric for evaluating model performance.
- **Best Performing Model**: The K-NN classifier emerged as the most accurate, with a 99.88% accuracy score.
- **Recommendation**: K-NN is the recommended model for deployment in predicting milk quality.

## Conclusions
The project demonstrated the effective application of machine learning in predicting milk quality, with the K-NN classifier recommended for future deployments. This study highlights the significant role of machine learning in enhancing food safety and quality control in the dairy industry.

## Inspiration
This work is inspired by the potential benefits of applying machine learning in the dairy industry, particularly for quality control and predictive analysis.
