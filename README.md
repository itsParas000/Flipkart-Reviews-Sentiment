# Project title:  Flipkart Reviews Sentiment Analysis using Python  


# Importing Libraries and Dataset:  
Load the necessary Python libraries like  
pandas  
matplotlib  seaborn  
scikit-learn  
WordCloud  

The project uses the Flipkart Reviews Dataset.
# flipkart_data.csv  



# Data Preprocessing:  
Clean the dataset by removing missing and duplicate values. The text is converted to lowercase, and stopwords, punctuation, and special characters are removed. Sentiment labels are encoded (Positive = 1, Negative = 0). The data is then tokenized using TF-IDF.  

<img width="926" height="142" alt="image" src="https://github.com/user-attachments/assets/b429d8b1-0714-419c-92c7-654ec4746adf" />



# Exploratory Data Analysis (EDA):  
Visualize the sentiment distribution using count plots and create a word cloud to identify common words in positive and negative reviews.  
# Sentiment Distribution  

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/b46c5e38-37ca-4d3a-b49a-9f1f8f33a1f6" />  

# WordCloud  

<img width="1182" height="306" alt="image" src="https://github.com/user-attachments/assets/1dc3f7c3-7d14-49e9-9f31-338c12e2f077" />  

# Review Length vs Sentiment  

<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/da4e5a08-8272-42fe-ba55-d3c8b9e8e8a1" />  

# Confusion Matrix  

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/b1103d83-6f26-46cd-8f82-7e46ffbcb67a" />  






# Model Training and Selection:  
Train different machine learning models, including Logistic Regression, Naïve Bayes, Random Forest Classifier, and Support Vector Machine (SVM), and compare their performance using accuracy and F1-score.  

<img width="596" height="317" alt="image" src="https://github.com/user-attachments/assets/6c165614-61b0-45e3-bdd3-0b4680c8e6e8" />  


# Model Evaluation and Prediction:  
Evaluate the best model using accuracy score, precision, recall, F1-score, and a confusion matrix. The final model can classify new reviews as positive or negative.  

<img width="542" height="236" alt="image" src="https://github.com/user-attachments/assets/fb9c4449-ebc2-4c05-86b3-45c45304a206" />
