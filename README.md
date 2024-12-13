# SMS Spam Detection  

## Overview  
SMS Spam Detection is a machine learning model that takes an SMS as input and predicts whether the message is spam or not spam. The model is built using Python and deployed on the web using Streamlit.  

---

## Technology Used  
- **Python**  
- **Scikit-learn**  
- **Pandas**  
- **NumPy**  
- **Streamlit**  

---

## Features  
1. Data Collection  
2. Data Cleaning and Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Model Building and Selection  
5. Web Deployment Using Streamlit  

---

## Data Collection  
The SMS Spam Collection dataset was sourced from Kaggle. It contains over 5,576 SMS messages labeled as either spam or not spam.  

Dataset Link: [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)  

---

## Data Cleaning and Preprocessing  
- Handled null and duplicate values.  
- Label-encoded the "type" column to map `spam` and `ham` messages to numerical values.  
- Preprocessed the text data by:  
  - Tokenizing text into words.  
  - Removing special characters, punctuation, and stop words.  
  - Applying stemming to reduce words to their root form.  
  - Converting all text to lowercase for uniformity.  

---

## Exploratory Data Analysis (EDA)  
- Calculated statistics like the count of characters, words, and sentences per message.  
- Analyzed correlations between variables.  
- Visualized the dataset using:  
  - Pyplot-based bar charts and pie charts.  
  - Five-number summaries and heatmaps.  
  - Word clouds for spam and non-spam messages.  
  - Frequency distributions of the most common words in spam texts.  

---

## Model Building and Selection  
- Experimented with various classifiers, including:  
  - **Naive Bayes**  
  - **Random Forest**  
  - **K-Nearest Neighbors (KNN)**  
  - **Decision Tree**  
  - **Logistic Regression**  
  - **ExtraTreesClassifier**  
  - **Support Vector Classifier (SVC)**  
- The best classifier achieved a precision of 100% and was selected for deployment.  

---

## Web Deployment  
- Deployed the model using **Streamlit** for an interactive user interface.  
- Features:  
  - A simple input box where users can input an SMS message.  
  - The model predicts whether the message is spam or not spam.  


 
