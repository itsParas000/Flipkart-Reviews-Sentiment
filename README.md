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

<img width="930" height="135" alt="image" src="https://github.com/user-attachments/assets/281375ba-a281-490a-9f5a-c657b040c7fa" />


# Exploratory Data Analysis (EDA):  
Visualize the sentiment distribution using count plots and create a word cloud to identify common words in positive and negative reviews.  
# Sentiment Distribution  

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/ccfdbdb1-945a-41c4-8fba-b6742c6b15be" />
 

# WordCloud  

<img width="1182" height="306" alt="image" src="https://github.com/user-attachments/assets/a2795c1b-bdee-4895-a0bf-19d1f6456d4f" />
  

# Review Length vs Sentiment  

<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/5cc4cbe1-dec6-4faa-b1ba-dce4f1aa078a" />


# Confusion Matrix  

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/f0b82d48-d0f6-4adb-83e9-b98b357df06c" />







# Model Training and Selection:  
Train different machine learning models, including Logistic Regression, Naïve Bayes, Random Forest Classifier, and Support Vector Machine (SVM), and compare their performance using accuracy and F1-score.  

<img width="580" height="312" alt="image" src="https://github.com/user-attachments/assets/926958d6-20ab-4dab-8f63-799a4a08fa9a" />



# Model Evaluation and Prediction:  
Evaluate the best model using accuracy score, precision, recall, F1-score, and a confusion matrix. The final model can classify new reviews as positive or negative.  

<img width="546" height="242" alt="image" src="https://github.com/user-attachments/assets/1ad1040a-836d-4c25-85ff-638a757a3d90" />
