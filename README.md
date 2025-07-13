# Yelp Review Sentiment Analysis

## Project Overview

Local businesses on Yelp often face challenges interpreting vast amounts of unstructured customer reviews. Despite having access to extensive user-generated content, many small business owners lack the tools to extract actionable insights, which limits their ability to improve customer satisfaction and operational performance.

This project aims to empower local businesses by leveraging machine learning and natural language processing (NLP) techniques to perform sentiment analysis on Yelp reviews. The goal is to help businesses:

- Improve customer retention and satisfaction  
- Make data-driven operational decisions  
- Optimize their Yelp presence to boost star ratings and visibility  



## Business Problem

- **Problem:** Local businesses struggle to interpret large volumes of unstructured Yelp reviews.  
- **Context:** Small business owners often lack analytics tools to extract insights from reviews.  
- **Impact:** Missed opportunities to improve products/services, leading to lower retention, weaker brand reputation, and lost revenue.



## Proposed Solution

### Objective
Enable local businesses to optimize Yelp strategies by analyzing review sentiment to improve customer engagement and operational decisions.

### Key Recommendations
- **Review Quality Optimization:** Identify keywords and tones that drive higher ratings.  
- **Predictive Customer Targeting:** Segment and retarget users likely to revisit or engage again.  
- **Geographic Expansion Insights:** Cluster review and check-in data to discover high-interest, low-competition locations for new outlets.

### Expected Business Impact
- Increase Yelp star ratings by approximately 0.2 to 0.5 on average.  
- Boost customer retention and re-engagement rates.  
- Achieve a 15–25% performance improvement through strategic location planning.



## Data and Methodology

### Data Source
- Yelp Open Dataset: Includes review text and star ratings.

### Data Processing
- Convert star ratings to binary sentiment labels (positive/negative).  
- Clean and preprocess review text.

### Feature Engineering
Text vectorization using:  
- Bag of Words  
- TF-IDF  
- n-Grams  

### Modeling Algorithms
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  

### Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC AUC  



## Results and Insights

- **Top Performing Model:** Logistic Regression with n-Gram features.  
- **Performance:**  
  - Accuracy: 94%  
  - Precision: 94%  
  - Recall: 94%  
  - F1 Score: 94%  
  - ROC AUC: 98%  

This model balances accuracy, interpretability, and minimizes false negatives, ensuring that unhappy customers are correctly identified without wasting resources on happy customers.



## Deployment

- Integration of the sentiment model into customer insight dashboards for real-time review analysis.  
- Scalable solution designed for continuous monitoring of customer sentiment at scale.



## Next Steps

- Finalize model selection after further validation.  
- Develop business-friendly dashboards and visualizations for easy interpretation by local business owners.  
- Prepare demo use cases, such as for coffee shops, to showcase actionable insights.



