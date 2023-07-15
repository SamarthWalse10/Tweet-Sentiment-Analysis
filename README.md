# Tweet-Sentiment-Analysis
Sentiment Classification of Tweets: Python-Based Approach using Bag-of-Words    

This project focuses on performing sentiment analysis on Twitter data using the Bag-of-Words approach. The objective is to classify tweets into three sentiment categories: negative, neutral, and positive.
## Dataset
The dataset utilized in this project is the Sentiment Dataset obtained from Kaggle, comprising a collection of 162,980 tweets extracted through the Twitter API. Each tweet is associated with a polarity label (positive, negative, or neutral) and includes the clean text of the tweet.
## Methodology
- Data Preprocessing: The dataset undergoes preliminary preprocessing steps, including the removal of NaN values and the normalization of text by converting it to lowercase.
- Vectorization: The Bag-of-Words technique is employed to transform the tweets into numerical feature vectors. This process involves constructing a vocabulary from the entire dataset and representing each tweet as a vector, where the elements indicate the presence or absence of words from the vocabulary.
- Classification: The vectorized data is split into training and testing sets (99% for training and 1% for testing). A classification model, such as Logistic Regression or any other appropriate classifier, is trained on the training set.
- Model Evaluation: The trained model is evaluated on the testing set to assess its performance. Accuracy, precision, recall, and F1-score can be calculated to measure the effectiveness of the sentiment classification.
## Installation
To utilize this sentiment analysis model for your own Twitter data, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/SamarthWalse10/Twitter-Sentiment-Analysis.git
2. Install the necessary dependencies.
3. Replace the twitter_data.csv file with your own dataset, maintaining the same format.
4. Execute the relevant Python script, such as sentiment_analysis.py, to perform sentiment analysis on your data.
