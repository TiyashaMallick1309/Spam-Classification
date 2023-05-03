# Spam Classifier

Spam Classifier is a machine learning model that can distinguish spam emails from ham emails.

## Overview
This project uses the Naive Bayes algorithm and the CountVectorizer class from scikit-learn's feature_extraction.text module to create a spam classifier.

## Dataset
The dataset used for training and testing the model is spam.csv, which contains a collection of spam and ham emails. <br/>
The dataset consists of 5572 rows and 2 columns: "label" and "email". The "label" column specifies whether the email is spam or ham, 
and the "email" column contains the text of the email.

## Installation
The following libraries are required to run the project:

* pandas
* matplotlib
* seaborn
* nltk
* scikit-learn

You can install these libraries using pip.

## Usage
The project consists of the following files:

* spam.csv: The dataset used for training and testing the model.
* spam_classifier.ipynb: The Jupyter notebook containing the code for the spam classifier.
* readme.md: The readme file that you are currently reading.

To use the spam classifier, follow these steps:

1. Clone the repository to your local machine.
2. Open the spam_classifier.ipynb file in Jupyter Notebook or JupyterLab.
3. Run the cells in the notebook to train and test the model.

The trained model can be used to predict whether an email is spam or ham.

## Credits
The dataset used in this project is taken from Kaggle.

## License
This project is licensed under the MIT License.
