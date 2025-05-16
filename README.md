# Sentiment Analysis for Product Reviews

This project applies Natural Language Processing (NLP) and machine learning techniques to perform sentiment analysis on Amazon product reviews. The aim is to classify customer feedback into Positive, Neutral, or Negative sentiments, with a focus on improving accuracy through sarcasm detection and ensemble modeling.

## Project Overview

- **Dataset**: Kaggle Amazon Product Reviews (balanced to 45,000 samples)
- **Techniques Used**:
- Text Preprocessing (cleaning, tokenization, lemmatization, negation handling)
- TF-IDF feature extraction
- Ensemble models: SVM, Logistic Regression, Multinomial Naïve Bayes
- Voting Classifier for final prediction
- Sarcasm detection using a pre-trained Hugging Face model
- Hyperparameter tuning with Optuna

## Results

- **Final Accuracy**: 80.66%
- **F1 Score**: ~0.81
- Enhanced sentiment prediction through sarcasm detection and ensemble learning.

## How to Use

1. Clone or download this repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter.
3. Run the cells to:
- Preprocess the data
- Train the ensemble model
- Evaluate model performance
4. The sarcasm flag is automatically included during preprocessing.
  
## Authors
- **Rohan Kumar**
