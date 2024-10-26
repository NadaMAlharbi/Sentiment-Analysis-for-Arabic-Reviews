# Sentiment Analysis for Arabic Reviews

**Author:** Nada Mohammed Alharbi  
**Project Type:** Academic Project for Natural Language Processing (NLP)

## Project Overview
This project involves building a sentiment analysis model using the Naive Bayes algorithm for classifying Arabic text reviews. Given the unique challenges of Arabic text processing, including complex morphology and dialectical variations, this project aims to deliver a reliable model for classifying reviews as positive, negative, or neutral.

## Table of Contents
1. [Dataset](#dataset)
2. [Model Architecture](#model-architecture)
3. [Training and Evaluation](#training-and-evaluation)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [How to Run](#how-to-run)
7. [Dependencies](#dependencies)

## Dataset
The dataset, `arabic-company-reviews`, contains reviews of various delivery companies. Each review is labeled with a sentiment score: `1` (positive), `-1` (negative), or `0` (neutral).

## Model Architecture
The baseline model for this project is a **Naive Bayes classifier**. Naive Bayes is commonly used in NLP tasks for its simplicity and effectiveness, especially in text classification. We utilize **Multinomial Naive Bayes** from `scikit-learn`, which is suited for text data represented as term frequencies. 

Additional steps include:
- **Lemmatization**: Used to normalize words to their base form, enhancing model accuracy.
- **Text Cleaning**: Removal of punctuation and stop words specific to Arabic.

## Training and Evaluation
The training process involves splitting the dataset into training and testing sets. We evaluate model performance using metrics like accuracy and F1-score to gauge how well it classifies sentiment in Arabic reviews.

## Results
The Naive Bayes model provided competitive accuracy in classifying Arabic reviews. The results demonstrate that Naive Bayes, combined with text preprocessing techniques, can effectively handle Arabic sentiment classification.

## Conclusion
This project establishes a strong foundation for Arabic sentiment analysis using Naive Bayes, offering insights into customer opinions and helping businesses understand public sentiment.

## How to Run
1. Ensure that all dependencies are installed (see the Dependencies section).
2. Open the `Sentiment Analysis for Arabic Reviews.ipynb` file.
3. Execute each cell in the notebook to preprocess the data, train the model, and evaluate the results.

## Dependencies
To run this project, the following packages are required:
- Arabic-Stopwords
- Tashaphyne
- qalsadi
- scikit-learn

