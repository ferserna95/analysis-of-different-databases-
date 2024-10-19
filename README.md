# Customer Personality Analysis for Marketing Optimization

This project analyzes the personality of customers of a company that sells products through various channels (physical store, website, catalog), using purchase data, campaigns and demographic characteristics.

## 📊 Project Objectives

- **Customer Segmentation**: Group customers according to purchasing behavior and demographic characteristics.
- **Identification of Popular Products**: Determine the most purchased products and the segments with the highest spending.
- **Campaign Effectiveness Evaluation**: Measure the effectiveness of marketing campaigns according to client characteristics.
- **Campaign Response Prediction**: Predict the probability that a customer will respond to future campaigns.
- **Optimization of Marketing Strategies**: Focus resources on the most valuable segments.

## 🛠️ Methodology

- **Segmentation**: Use of the Elbow Method to determine the optimal number of clusters (3 suggested clusters).
- **Campaign Effectiveness Analysis**: Visualization of response rates, segmentation by demographic characteristics and ROI analysis.
- **Predictive Models**: Classification with Random Forest to predict the response to campaigns based on income, total spending and in-store purchases.

## ⚡ Key Results

- **Identified Segments**: Three main segments:
  - High income/expense
  - Young people with low spending
  - Frequent buyers in stores
- **Campaign Response Rate**: The overall rate is low (7% max.), but certain segments respond better.
- **Model Accuracy**: 84% accuracy, although the ROC AUC is low (0.55), which indicates opportunity for improvement.
