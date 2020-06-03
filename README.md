
# Sentiment Anaysis Of Movie Reviews

## Project Overview
This is a simple project to classify movie reviews as either positive or negative (binary classification problem).The dataset we use is the popular IMBD movie dataset.It is a csv file with columns `review` and `sentiment` where `sentiment` is either `1` (positive) or `0`(negative).

## Algorithm
Text Analysis is a major application field for machine learning algorithms. However the raw data, a sequence of symbols cannot be fed directly to the algorithms themselves as most of them expect numerical feature vectors with a fixed size rather than the raw text documents with variable length.
In order to address this, scikit-learn provides utilities for the most common ways to extract numerical features from text content, namely:
* **tokenizing** strings and giving an integer id for each possible token, for instance by using white-spaces and punctuation as token separators.
* **counting** the occurrences of tokens in each document.
* **normalizing** and weighting with diminishing importance tokens that occur in the majority of samples / documents.
A corpus of documents can thus be represented by a matrix with one row per document and one column per token (e.g. word) occurring in the corpus.
We call **vectorization** the general process of turning a collection of text documents into numerical feature vectors. This specific strategy (tokenization, counting and normalization) is called the **Bag of Words** or **Bag of n-grams** representation. 

## Results
* Accuracy - 89.5%
* Precision - 88.9%
* Recall - 90.2%
* F1-Score - 89.5%

## Software And Libraries
This project uses the following software and libraries:
*[python 3.8.0](https://www.python.org/downloads/release/python-380/)
*[Jupyter Notebook](https://jupyter.org/)
*[pandas](https://pandas.pydata.org/)
*[NumPy](https://numpy.org/)
*[scikit-learn](https://scikit-learn.org/stable/)
*[pickle](https://docs.python.org/3/library/pickle.html)
*[Natural Language Toolkit](https://www.nltk.org/)

## Contact
Email: pranaykankariya97@gmail.com
Project Link: [https://github.com/pranaykankariya97/Sentiment-Analysis-Movie-Reviews](https://github.com/pranaykankariya97/Sentiment-Analysis-Movie-Reviews)

