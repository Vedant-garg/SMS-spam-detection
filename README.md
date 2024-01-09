# SMS Spam Detection Model

This project implements a machine learning model to classify SMS messages as spam or ham (non-spam). The model is built using the Multinomial Naive Bayes classifier and utilizes the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique for text representation.

## Project Structure

- `SMS-spam-detection.ipynb`: Jupyter Notebook containing the code for data cleaning, EDA, data preprocessing, and model building.
- `spamdataset.csv`: Dataset used for training the model.
- `vectorizer.pkl`: Pickle file containing the TF-IDF vectorizer used to transform text data.
- `model.pkl`: Pickle file containing the trained Multinomial Naive Bayes classifier.

## How to Use

1. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud xgboost
