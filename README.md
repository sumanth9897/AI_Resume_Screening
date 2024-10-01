# Resume Screening 

## Overview

This project involves a straightforward resume classification system that categorizes resumes into specific job categories. The classification is performed using a K-Nearest Neighbors (KNN) classifier, trained on a dataset of resumes.

## Features

- **Data Exploration:** Analyze the provided dataset to gain insights into the distribution of resume categories through visualizations
- **Text Cleaning:** Utilize the `cleanResume` function to preprocess resume text, removing unnecessary elements like URLs, mentions, and punctuations.

- **Word Cloud:** Generate a word cloud to visualize the most frequent words in the cleaned resume text using the `wordcloud` library.

- **Feature Extraction:** Use the `TfidfVectorizer` from scikit-learn to convert the cleaned text into numerical features suitable for machine learning.

- **Model Training:** Train a KNN classifier using the `OneVsRestClassifier` approach and evaluate its accuracy on training and test sets.

- **Making Predictions:** Allow users to input new resume text, and the model will predict its category, providing probability scores for each category.

- **Category Descriptions:** Provide brief descriptions of predicted categories based on the top predicted category.

## Prerequisites

Ensure you have the necessary libraries installed. You can install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
```

## Dataset
The project uses the UpdatedResumeDataSet.csv dataset, containing labeled resumes for training and evaluation.

