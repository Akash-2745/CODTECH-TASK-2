**Name:** P. DEVI SRI AKASH  
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT08DS8497 
**Domain:** Data Analytics  
**Duration:** SEPTEMBER 25 to OCTOBER 25 2024

## SOCIAL MEDIA SENTIMENT ANALYSIS

### Introduction
This project aims to analyze social media data (tweets) to detect hate speech, specifically racist or sexist content. The objective is to classify tweets as containing hate speech or not using machine learning techniques.

### Dataset
- Size: 31,962 labeled tweets.
- Features: Text content of tweets.
- Labels: Binary classification (1 for hate speech, 0 for non-hate speech).
  
### Methodology

#### 1. Data Preprocessing:
 - Removal of Twitter handles, special characters, and numbers.
 - Tokenization and stemming.

#### 2. Exploratory Data Analysis (EDA):

 - Visualization of frequent words and hashtags.
  
![image](https://github.com/user-attachments/assets/024ba065-504f-4cb7-a3a5-302639c20b79)

![image](https://github.com/user-attachments/assets/dad64294-afb9-4c37-b6e3-599672eeb6d1)

![image](https://github.com/user-attachments/assets/f98389bb-a6b8-4ce0-bef8-1f2bccaba66b)

![image](https://github.com/user-attachments/assets/f58a9d47-feb1-4272-8749-0a67f4a7a155)

#### 3. Feature Extraction:

 - Conversion of text data to numerical matrices using CountVectorizer.

#### 4. Model Training and Evaluation:

 - Logistic Regression model trained on bag-of-words representation.
 - Performance evaluation using accuracy, F1-score, and ROC AUC score.
 - Confusion matrix visualization for analyzing predictions.

![Screenshot 2024-08-22 191759](https://github.com/user-attachments/assets/1d7c4ce1-cca8-431d-a889-4298f7cc9f10)


### Results
- Trained model achieved 95% accuracy.
- F1-score was 54% and ROC AUC score were 94%, respectively.
- Confusion matrix provided insights into model performance.

### Conclusion
This project demonstrates the application of NLP and machine learning for social media sentiment analysis, aiding in the detection of hate speech. Future work includes exploring advanced NLP models and real-time deployment.






