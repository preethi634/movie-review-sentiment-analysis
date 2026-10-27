# movie-review-sentiment-analysis# Movie Review Sentiment Analysis using NLP and Machine Learning

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify movie reviews as **positive** or **negative**. It explores text preprocessing, TF-IDF feature extraction, model training, evaluation, and improvements using additional labelled examples.

## Objectives

- Clean and preprocess textual data.
- Explore sentiment labels and word patterns.
- Convert text into numerical features using TF-IDF.
- Train and compare machine learning classification models.
- Evaluate model performance on held-out test data.

## Dataset

- **Dataset:** NLTK Movie Reviews corpus
- **Total reviews:** 2,000
- **Positive reviews:** 1,000
- **Negative reviews:** 1,000

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorization
- Logistic Regression
- Linear Support Vector Machine (Linear SVM)
- Google Colab

## Project Workflow

1. Load the movie review dataset.
2. Perform exploratory data analysis (EDA).
3. Clean and preprocess review text.
4. Convert text into TF-IDF features using unigrams and bigrams.
5. Train and compare machine learning models.
6. Evaluate predictions using accuracy, precision, recall, and F1-score.
7. Add a small set of manually labelled examples to the training data and evaluate the augmented model.

## Model Results

The augmented Logistic Regression model achieved **88.25% accuracy** on the 400-review held-out test set.

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Negative | 0.88 | 0.89 | 0.88 |
| Positive | 0.88 | 0.88 | 0.88 |

These results reflect performance on this dataset and test split. They do not guarantee the same performance on other types of text.

## Key Learning Outcomes

- Text preprocessing and feature extraction for NLP.
- Training and evaluating text classification models.
- Comparing machine learning models.
- Understanding the limitations of TF-IDF and sentiment classification.
- Investigating model predictions and improving training examples.

## Limitations

- The model can struggle with negation, mixed opinions, sarcasm, and very short sentences.
- The additional labelled examples are limited and manually created.
- Further evaluation on diverse, unseen text is needed to assess generalization.

## Future Improvements

- Improve handling of negation and mixed sentiment.
- Test on additional unseen reviews.
- Explore pretrained sentiment analysis models.
- Develop a Gradio web interface for interactive predictions.

## How to Run

1. Open `sentiment_analysis.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Install any missing dependencies if prompted.
4. Review the model evaluation and example predictions.

## Project Status

**Machine learning notebook completed.** A Gradio application is planned as a future enhancement.

