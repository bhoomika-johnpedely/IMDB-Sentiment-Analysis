### Project Overview
#### Title: IMDB Sentiment Analysis

#### Introduction
This project aims to train a sentiment analysis model on an IMDB dataset with 50k reviews. The dataset can be directly imported from the datasets library in Python. This is a supervised classification problem. The model will be trained to classify the reviews as either positive or negative and then be evaluated on the test set. The benchmark accuracy for this project is between 80-85%.  

#### Data Preprocessing and Features Extraction

- I took a smaller subset of only 3k reviews from the imported train and test datasets each to work with my machine's limited technological capacity.
- I lowercased and tokenized both the train and test sets.
- I removed stopwords, punctuations, digits and special characters.
- I used lemmatization to reduce dimensionality.
- I used TF-IDF for effective feature extraction.
 
#### Modeling

- I experimented with and trained 3 different models (Logistic Regression, Multinomial Naive Bayes, Linear SVM) using the train set and evaluted on the test set. 
- Logistic Regression and Linear SVM, both acheived an accuracy of 83.7% while Multinomial Naive Bayes achieved an accuracy 81.8%.

#### Conclusion

I developed a machine learning model for sentiment analysis on IMDb movie reviews, utilizing NLP techniques and Python libraries (NLTK and Scikit-Learn) to accurately classify user sentiment as positive or negative. I conducted data preprocessing and noise reduction to achieve model accuracy 83.7%, ensuring clean and reliable results in sentiment classification.

#### Next Steps
If I have access to better memory and processing power, I would train this sentiment analysis model on the entire dataset with 50k reviews, potentially improve model performance. 
