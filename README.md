# Customer Review Sentiment Classifier

## Overview
This project uses Natural Language Processing (NLP) and machine learning to classify movie reviews as positive or negative. It uses the Movie Reviews dataset provided by NLTK to explore how text preprocessing and feature extraction can support sentiment classification.

## Technologies Used
- Python
- NLTK
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF Vectorization
- Logistic Regression
- Multinomial Naive Bayes

## Project Workflow
1. Loaded the Movie Reviews dataset from NLTK.
2. Cleaned and preprocessed the review text.
3. Explored the dataset and examined sentiment distribution.
4. Split the data into training and testing sets using stratified sampling.
5. Converted text into numerical features using TF-IDF vectorization.
6. Trained and compared Logistic Regression and Multinomial Naive Bayes models.
7. Evaluated model performance using accuracy, classification metrics, confusion matrices, and error analysis.

## Results
- Dataset: 2,000 movie reviews.
- Classes: 1,000 positive and 1,000 negative reviews.
- Best model: Logistic Regression.
- Test accuracy: 82.75%.

## Key Learning Outcomes
- Text preprocessing and NLP fundamentals.
- TF-IDF feature extraction.
- Training and comparing machine learning classifiers.
- Evaluating classification performance and analysing misclassified reviews.

## Future Improvements
- Experiment with additional text preprocessing techniques.
- Evaluate other NLP models.
- Test the model on a different review dataset to assess generalisation.

## Disclaimer
This project uses the NLTK Movie Reviews corpus and is intended for educational purposes.
