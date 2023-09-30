A Python program for classifying resumes into "flagged" and "not flagged" categories using natural language processing (NLP) and machine learning.

## Introduction

The Resume Classification Program is designed to automate the process of categorizing resumes based on their content. It utilizes NLP techniques and the Multinomial Naive Bayes algorithm to classify resumes into two categories: "flagged" (potentially relevant) and "not flagged" (not relevant). This program can be valuable in scenarios where you need to sift through a large number of resumes quickly.


## Features

Automatic classification of resumes into "flagged" and "not flagged" categories.
Data preprocessing to clean and prepare resume text.
Visualization of classification results, including confusion matrices.
Performance evaluation using metrics such as accuracy, precision, recall, and F1-score.
Getting Started
Follow these instructions to set up and run the Resume Classification Program on your system.


## Prerequisites

Ensure you have the following prerequisites installed:
Python 3.x


Required libraries:
pandas, numpy, matplotlib, seaborn, NLTK, gensim, scikit-learn, wordcloud
You can install the required libraries using pip: pip install pandas, numpy, matplotlib, seaborn, nltk, gensim, scikit-learn, wordcloud.


## Usage

The program loads the resume dataset, preprocesses the text data, and visualizes the cleaned dataset.
It applies a Multinomial Naive Bayes classifier to automatically classify resumes into "flagged" and "not flagged" categories.
Classification results, including confusion matrices, are displayed for both training and test data.
Performance metrics such as accuracy, precision, recall, and F1-score are printed to assess the model's performance.


## Author
devanshu3
