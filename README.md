# Text_Classification

## Introduction
This project aims to classify text documents into different categories using the Naive Bayes algorithm. The dataset used is the `fetch_20newsgroups` dataset, which contains around 20,000 newsgroup documents spread across 20 categories.  

## Steps
**1. Import Libraries**  
Import necessary libraries such as pandas, sklearn, and others required for data processing, feature extraction, and model training.  

**2. Load Dataset**  
Load the fetch_20newsgroups dataset from sklearn. This dataset includes a variety of newsgroup posts organized into 20 different categories.  

**3. Split Dataset**  
Split the dataset into training and testing sets .  

**4. Feature Extraction**  
Convert the text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization with TfidfVectorizer from sklearn.  

**5. Train Naive Bayes Classifier**  
Train a Naive Bayes classifier (MultinomialNB) on the training data.  

**6. Make Predictions**  
Use the trained Naive Bayes model to make predictions on the test data.  

**7. Evaluate Model**
Evaluate the performance of the model using metrics such as accuracy. These metrics provide insights into the effectiveness of the classifier.  

## Results
Accuracy: 77%
