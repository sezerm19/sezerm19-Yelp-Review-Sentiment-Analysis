# **Yelp Review Sentiment Analysis**

## **About the Project**
This project focuses on performing sentiment analysis on Yelp reviews. Users rate their experiences with a 1 to 5-star rating system, and this data is utilized to classify the reviews using machine learning and natural language processing (NLP) techniques. The goal is to derive meaningful insights into customer satisfaction and provide data-driven recommendations for improving service quality.

## **Objectives**
1. Process and clean Yelp review text data for analysis.
2. Use Natural Language Processing (NLP) techniques for sentiment extraction.
3. Build machine learning and deep learning models for sentiment classification.
4. Evaluate model performance and visualize results.

## **Technologies and Methods**
- **Programming Language**: Python
- **Data Processing**: Pandas, NumPy
- **Natural Language Processing (NLP)**:
  - TF-IDF Vectorization
  - Stop Words Removal
- **Modeling**:
  - Scikit-learn (Random Forest, Logistic Regression)
  - TensorFlow / Keras (Deep Learning Models)
- **Data Visualization**: Matplotlib, Seaborn
- **Evaluation Metrics**:
  - Accuracy
  - F1 Score
  - Confusion Matrix


## **Results**
Key findings from the sentiment analysis project are summarized below:

- **Best Model Performance**:
  - Model: **Revised Dropout Model NN**
  - Classification Report:
```plaintext
              precision    recall  f1-score   support

     Class 0       0.66      0.73      0.69      1871
     Class 1       0.48      0.45      0.46      1880
     Class 2       0.47      0.43      0.45      1903
     Class 3       0.48      0.45      0.46      1903
     Class 4       0.63      0.68      0.65      1955
    
    accuracy                           0.55      9512
   macro avg       0.54      0.55      0.54      9512
weighted avg       0.54      0.55      0.54      9512
```
  - Confusion Matrix: 
    - High accuracy in correctly predicting 5-star and 1-star reviews.
    - Minor misclassifications observed between 3-star and 4-star reviews.



- **Overall Insights**:
  - TF-IDF vectorization provided robust features for machine learning models.
  - The deep learning model outperformed traditional machine learning models in handling complex patterns within the review text.
  - Visualizations revealed clear sentiment separation for extreme classes (1-star and 5-star).

Performance visualizations are available in the `visuals/performance_plot.png` file, showcasing:
1. Accuracy comparison across models.
2. Confusion matrix heatmaps for model evaluation.
3. Precision-Recall and ROC curves for the final model.

These results demonstrate the efficacy of using deep learning techniques combined with proper feature engineering for sentiment analysis tasks.
