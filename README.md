# Smartphone Accelerometer Analysis for Heavy Drinking Detection

## Project Overview
The primary objective is to create a user-friendly and reliable tool that can accurately identify patterns associated with heavy alcohol consumption based on motion data captured by smartphones. This tool will utilize advanced machine learning algorithms to analyze accelerometer readings and detect anomalies indicative of excessive drinking behavior. Additionally, the tool will prioritize user privacy and data security, ensuring that sensitive information is handled with utmost confidentiality. The ultimate goal is to provide individuals with valuable insights into their drinking habits, promote responsible alcohol consumption, and potentially facilitate early intervention measures for those at risk of alcohol-related harm.

## Task
1. **Understand the Dataset**: Analyze the dataset provided for the project ([Dataset Link](https://archive.ics.uci.edu/dataset/515/bar+crawl+detecting+heavy+drinking)).
2. **Investigate Permutation Entropy and Complexity Method**: Assess the reliability of permutation entropy and complexity methods in differentiating heavy drinking vs. sober cases.

## Code Implementation
### Data Preprocessing
- The provided Jupyter notebook preprocesses 14057567 rows of accelerometer data obtained from smartphone sensors. 
- It merges accelerometer data with transdermal alcohol content (TAC) readings to create a unified dataset for analysis.
- Data preprocessing steps include cleaning, filtering, and aligning the data to ensure accuracy and consistency.

### Time Series Analysis
- An extensive time series analysis is conducted on the smartphone accelerometer data from 13 participants.
- The effectiveness of permutation entropy and complexity methods in discerning heavy drinking from sober cases is assessed.
- This analysis provides crucial insights into participants' drinking habits and patterns of alcohol consumption.

### Model Development
- Logistic regression and decision tree classifiers are employed to develop predictive models for heavy drinking detection.
- The models achieve remarkable accuracy rates of 100%, demonstrating their robustness and reliability in accurately identifying instances of heavy drinking based on accelerometer data.

## Classification Results
- Both logistic regression and decision tree classifiers achieved a perfect accuracy of 1.00.
- Confusion matrices show no misclassifications, with all predictions falling on the diagonal, indicating perfect classification.
- Precision, recall, and F1-score values for both classes (0 and 1) are also 1.00, indicating optimal performance for both classes.
- These results suggest that the models are highly effective in distinguishing between the two classes, achieving perfect accuracy on the test data.

## Conclusion
- The dataset contains clear patterns that enable the models to achieve perfect classification accuracy.
- Features such as TAC_Reading, permutation entropy, complexity, sober indicator, and various participant ID categories are highly informative and discriminative, allowing for accurate predictions.
- The developed models showcase the potential of accelerometer data and advanced machine learning algorithms in detecting heavy drinking behavior, providing valuable insights into individuals' drinking habits and promoting responsible alcohol consumption.
