# Hate Speech Identification Model

This project aims to develop a classifier using the NLTK and scikit-learn libraries to categorize given text into offensive, hate speech, or neither. It leverages machine learning techniques to contribute to addressing the issue of hate speech online.

## Motivation

Machine learning for the greater good. With the knowledge of natural language processing (NLP) and machine learning models, I chose to invest my time in this project as I believe learning the skills to combat hate speech and offensive language is crucial in today's digital age.

## Data Source

The dataset used to train the model consists of tweets, acquired from [Kaggle](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset). It provides a diverse collection of text samples based on tweets to train and test the hate speech identification model.

## Models Used

The following machine learning models were explored and implemented:

- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression

## Conclusion

| Model          | Precision | Recall | F1-score | Accuracy | Time     | Memory   |
| -------------- | --------- | ------ | -------- | -------- | -------- | -------- |
| Logistic Regression | 0.84      | 0.75   | 0.76     | 0.75     | 0.089 sec | 317.29 MiB |
| SVM            | 0.84      | 0.73   | 0.75     | 0.73     | 41.4 sec  | 453.25 MiB |
| Decision Tree  | 0.83      | 0.74   | 0.76     | 0.74     | 0.111 sec | 269.71 MiB |
| Naive Bayes    | 0.83      | 0.70   | 0.73     | 0.70     | 0.422 sec | 851 MiB    |
| KNN            | 0.87      | 0.68   | 0.73     | 0.68     | 14.88 sec | 851 MiB    |

As we can see that considering both scores and performance there's a tie between Logistic Regression and Decision Tree. While Decision Tree utilizes less memory but takes a tad bit longer and the scores are also similar.
Therefore we have also proved the no free lunch theorem which basically states there is no correct answer...



