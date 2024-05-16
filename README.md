# Twitter Sentiment Analysis

Sentiment Analysis is done by classifying the tweets as positive, negative and neutral by MultinomialNB.
The Sentiment140 dataset, comprising labeled tweets, was employed for sentiment analysis, aiming to predict sentiment in text. After initial data cleaning to eliminate noise, text representation was achieved via Bag-of-Words (BoW). The dataset was divided into 80% training and 20% testing sets. Utilizing Naive Bayes, a common NLP algorithm, the model underwent training and evaluation on metrics like accuracy and F1-score. Hyperparameter tuning, employing GridSearchCV, optimized model performance. 

Naive Bayes was my preferred choice for the tweet sentiment analysis project due to its efficiency, effectiveness in text classification, capability for probability estimation, and solid performance.



## Run Locally


  1. Clone the project

```bash
  git clone https://github.com/iaayushmaan/Twitter-Sentiment-Analysis.git
```

2. Go to the project directory

```bash
  cd ./Twitter-Sentiment-Analysis
```

3. Enter your `KAGGLE_USERNAME` and `KAGGLE_KEY` in the second cell

5. You are good to go!




> [!TIP]
> *Run on Colab instead. It's hassle-free!*  &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EkPg0MVoiy4oh9Lw2HXjZ-t4IlPMpORp?usp=sharing)

## Observations

The model achieved an overall accuracy of approximately 78.09% on the test data, indicating the percentage of correctly predicted labels. Precision for positive sentiment, measuring the accuracy of positive predictions, stands at approximately 80.42%. The recall for positive sentiment, representing the model's ability to identify positive instances correctly, is about 74.45%. The F1-score for positive sentiment, a balanced measure of precision and recall, is around 77.32%.

Through grid search, the best hyperparameters were identified: an alpha value of 1.0 and 'fit_prior' set to False, resulting in the highest accuracy during fine-tuning.

Upon evaluating these metrics with the best model and hyperparameters on the test data, results remained consistent with the initial evaluation, indicating minimal impact on model performance from fine-tuning.

