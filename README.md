# Aviation Company Digital Advertisement Targeting Model

## Project Overview

This project aims to develop targeted digital advertisement models for an aviation company looking to improve its marketing strategy. Instead of traditional tele-calling methods, the company has opted for digital advertising on a social networking platform. By leveraging the digital and social behavior of potential customers, the company aims to increase the efficiency and accuracy of its marketing efforts.

## Business Problem

The aviation company wants to implement a targeted approach to reach potential customers digitally. They have collaborated with a social networking platform to analyze the digital and social behavior of users and deliver advertisements to individuals with a high propensity to purchase tickets. The company needs separate models for laptop and mobile users due to differences in buying propensity across different login devices.

## Need of Study

1. **Impact of Digital Media on Tourism**: Understanding the influence of digital media on the tourism industry is crucial for adapting marketing strategies effectively.
2. **Social Media Marketing**: Leveraging social media platforms for marketing can lead to increased exposure, traffic, and sales at a lower cost.
3. **Consumer Behavior Analysis**: Analyzing online consumer behavior helps in understanding their preferences and decision-making processes, aiding in targeted advertising.

## Understanding Business/Social Opportunity

1. **Brand Building and Customer Communication**: Social media plays a vital role in brand building and customer communication for businesses of all sizes.
2. **Targeted Advertising**: By understanding customer behavior on social media, companies can target advertisements more effectively, resulting in higher conversion rates.
3. **Customer Feedback Utilization**: Analyzing customer feedback on social media helps in identifying and addressing issues, improving overall revenue and customer satisfaction.

## Modelling Approach Used & Why

### Steps Before Model Building

1. **Data Preprocessing**: Handling missing values, outliers, and scaling the data to ensure uniform variance.
2. **Variable Transformation**: Creating separate datasets for laptop and mobile users and adding new variables if necessary.
3. **Train-Test Split**: Dividing the dataset into training and testing sets in a 70:30 ratio.

### Different Types of Models Used

1. **Logistic Regression**: Modeling the probability of a binary outcome based on input variables.
2. **K-Nearest Neighbors (KNN)**: Classifying data points based on the majority class of their k-nearest neighbors.
3. **Naïve Bayes**: Classifying data based on the Bayes' Theorem with an assumption of independence among predictors.
4. **Bagging**: Improving the performance of existing ML algorithms, especially tree-based algorithms, in a parallel manner.
5. **ADA Boosting**: Increasing the efficiency of binary classifiers by sequentially learning from previous classifiers.
6. **Gradient Boosting**: Similar to ADA Boosting but correcting errors by adding under-fitted predictions to the ensemble.

### Three Types of Approach Used

1. **Base Models**: Building models without hyperparameter tuning.
2. **Model Tuning**: Maximizing model performance by selecting appropriate hyperparameters.
3. **SMOTE Technique**: Addressing data imbalance using the Synthetic Minority Oversampling Technique.

## Repository Contents

1. **Data Preprocessing Scripts**: Scripts for handling missing values, outliers, and scaling.
2. **Modeling Scripts**: Scripts for building various models including logistic regression, KNN, Naïve Bayes, bagging, ADA boosting, and gradient boosting.
3. **Model Evaluation Scripts**: Scripts for evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
4. **Documentation**: Additional documentation explaining the code, models, and results in detail.
5. **Requirements.txt**: List of required Python libraries for running the scripts.

## Conclusion

By implementing targeted digital advertisement models, the aviation company can improve its marketing strategy, increase customer engagement, and ultimately boost revenue. This project provides a comprehensive framework for developing and evaluating such models, enabling the company to make informed decisions based on data-driven insights.

