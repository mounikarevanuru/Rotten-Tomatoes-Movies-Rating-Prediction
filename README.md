# Movie Status Prediction and Sentiment Analysis

This project aims to predict movie status (Fresh, Rotten, Certified Fresh) using machine learning techniques such as **Decision Trees** and **Random Forests**. Additionally, it explores **sentiment analysis** of movie reviews to predict movie status based on review sentiment, employing **Random Forest Classifier** with and without class weighting.

## Table of Contents
- Project Overview
- Methodology
  - Decision Tree and Random Forest Classifiers
  - Sentiment Analysis Approach
- Results

## Project Overview

This project uses **movie review data** from Rotten Tomatoes to predict movie status labels such as **Fresh**, **Rotten**, and **Certified Fresh** based on multiple features, including ratings and critic counts. Additionally, we explore predicting movie status based on the sentiment of reviews using **Sentiment Analysis** with **Random Forest** models. 

We employ three variants of Random Forest:
- **Standard Random Forest**
- **Random Forest with Feature Selection**
- **Weighted Random Forest** (to address class imbalance)

## Methodology
### Decision Tree and Random Forest Classifiers
In this part of the project, we use Decision Tree Classifier and Random Forest Classifier for the prediction of movie status. These classifiers are trained using various features of the dataset, including audience ratings, critic scores, and more. The Random Forest models are trained with and without feature selection and class weighting.

Constrained Decision Tree: A decision tree with limited depth (restricted to 3 nodes).
Unconstrained Decision Tree: A fully trained decision tree without any restriction on depth.
Random Forest Classifier: Trained using all available features for the classification task.
Weighted Random Forest: We use class weighting to address the imbalance between the classes, adjusting the importance of each class.
Sentiment Analysis Approach
The second part of the project involves predicting the movie status based on the sentiment of reviews. This is done using Natural Language Processing (NLP) techniques, specifically:

Text Vectorization: The review content is vectorized using CountVectorizer.
Sentiment Analysis: We categorize reviews into two classes — Fresh and Rotten — based on the sentiment expressed in the review.
Random Forest: We train the Random Forest Classifier using both weighted and unweighted variants to predict the review sentiment.
Results
The models were evaluated using standard metrics such as accuracy, precision, recall, and F1-score.

Decision Tree: The constrained and unconstrained models produced high accuracy for predicting movie status, with the unconstrained model yielding slightly higher performance.

### Random Forest: 
Both standard and weighted variants performed exceptionally well, with the weighted model addressing the class imbalance effectively.
### Sentiment Analysis: 
The Weighted Random Forest classifier performed better at predicting the movie status based on sentiment, as it handled class imbalances and varying review lengths more effectively.

### Results
The models were evaluated using standard metrics such as accuracy, precision, recall, and F1-score.

Decision Tree: The constrained and unconstrained models produced high accuracy for predicting movie status, with the unconstrained model yielding slightly higher performance.
Random Forest: Both standard and weighted variants performed exceptionally well, with the weighted model addressing the class imbalance effectively.
Sentiment Analysis: The Weighted Random Forest classifier performed better at predicting the movie status based on sentiment, as it handled class imbalances and varying review lengths more effectively.
