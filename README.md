# Polyglot

Classify code snippets into programming languages with a Python module `scikit-learn` for machine learning.

## Description

This project is about supervised machine learning algorithms that uses labeled data to predict outputs based on inputs. The task is to create a classifier that can take snippets of code and guesses the programming language of the code.

## Motivation

The motivation of this project is to:

- Understand feature extraction
- Understand classification
- Understand the varied syntax of programming languages
- Be able to build a robust classifier

## Important links

HTML documentation: http://scikit-learn.org

## Special Instructions

User must import the following libraries:

- from sklearn.naive_bayes import MultinomialNB
- from sklearn.feature_extraction.text import CountVectorizer
- from sklearn.pipeline import Pipeline
- from sklearn.cross_validation import train_test_split
- import glob

## Testing

The `test` folder in the repository contains 32 files with the snippets of code in different programming languages.
