# udacity_project


## Introduction
In this project the task is to predict whether a comment posted on social media contains any violent language features. This is done with NLP processing and recurrent neural networks.
In the code there are 2 models for 2 different dataset 

* Detecting Insults in Social Commentary: with one target variable indicating whether a comment is an insult or not 
* Toxic Comment Classification Challenge: with six different target categories 
    
    * toxic
    * severe toxic
    * insult 
    * threat 
    * obscene
    * identity_hate
    
    This six categories are supposed to be modelled together, i.e. the prediction should return a 6-dim vector, where each entry indicates whether each category is hit



## Data requirements

For this assignment 2 datasets from Kaggle where used 

* [Detecting Insults in Social Commentary ](https://www.kaggle.com/c/detecting-insults-in-social-commentary/data) : Here download only the training set and save it in the same folder as Project.ipynb with the name train_data1.csv
* [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) : Here download only the training set and save it in the same folder as Project.ipynb with the name train.csv


Additionally we require the word embedding Glove 6B from Stanford University from [Global vectors for word representation](https://nlp.stanford.edu/projects/glove/) and download glove.6B.zip and save the word embedding called glove.6B.100d.txt into the folder glove.6B 


## Packages

In order to use this model it is necessary to download the following packages
* nltk.download('book')

The other packages are given in the jupyter notebook code 


## Working with code

If changes by you are added, upload and commit it with the description of what has been changed

