# Sentiment Analysis Using NLU

## Project Description
This project explores Sentiment Analysis through Natural Language Understanding (NLU) techniques. The system classifies emotions in tweets into categories like **Joy**, **Sadness**, **Anger**, and **Fear**, using various machine learning models. The dataset contains 20,000 labeled tweets, enabling robust model training and testing.

## Dataset
The Twitter Emotion Classification dataset was utilized, containing labeled sentences for classification. Classes **Love** and **Surprise** were excluded due to insufficient data.

## Models Implemented
1. **Logistic Regression**
   - Validation Accuracy: 93.45%
2. **Naive Bayes**
   - Validation Accuracy: 85.29%
3. **LSTM**
   - Validation Accuracy: 95.29%

LSTM performed best among the implemented models.

## Preprocessing Steps
- **Lowercasing:** Convert text to lowercase.
- **Tokenization:** Split text into words.
- **Stop Words Removal:** Remove non-informative words.
- **Lemmatization:** Convert words to their base forms.

## Additional Features
- **Speech Recognition:** Converts speech to text for input processing.
- **Text-to-Speech:** Generates interactive responses based on detected sentiment.

## Results
LSTM achieved the best validation accuracy of 95.29%, showcasing its effectiveness for sentiment classification tasks.

## Dataset Link
[Twitter Emotion Classification Dataset](https://www.kaggle.com/code/shtrausslearning/twitter-emotion-classification/input?select=training.csv)
