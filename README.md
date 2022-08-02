# Topic Modeling using Latent Dirichlet Allocation (LDA)

This repository presents a simple application of the Latent Dirichlet Allocation (LDA) model for topic modeling. The project consists of applying the LDA model to the document collection of the GT-8 ENANCIB (Information and Technology of the National Meeting of Research in Information Science).

## Collection
* The corpus consists of 273 documents (full articles and extended abstracts between 2012 and 2019).

## Requirements
* Python3
* python3.8-venv

## Exploratory Data Analysis
* Wordcloud

## Data pre-processing
* Conversion of terms
* Stopwords configuration
* Bigram e trigram models
* Tokenization

## What can still be done
* Removal of words less than 3 characters
* Removal of irrelevant words
* Stemming e Lemmatization

## How to run
* Start the project by preparing the environment through the command:
```
$ source prepare-env.sh
```
* Now you can use the notebook ```TopicModel_LDA``` in your prefer code editor.