# Identifying Duplicate Questions on Quora

## Goal


Identify duplicate questions in a dataset provided by Quora. This dataset contains more than 400,000 questions and was labeled by human experts which is an expensive process. The model I will build will need to automatically identify and label duplicate questions.

**Contributors:** Ali Bahrami

## Tools used


1. **Data Exploration:** Python
2. **Data Cleaning:** tokenization, punctuation removal, stopwords cleaning, normalizing, stemming
3. **Feature Engineering**: Word2Vec
4. **Modeling**: Logistic Regression, Random Forest Classifier

## Data


You can find the dataset in the data folder and also in:

[Quora Questions Dataset](https://drive.google.com/file/d/19iWVGLBi7edqybybam56bt2Zy7vpf1Xc/view)

You can find the pre-trained Google Word2Vec Model here: 

[Word2Vec from Google](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?resourcekey=0-wjGZdNAUop6WykTtMip30g)

## File Directory


- **data:** contains the data
- **presentation:** contains the presentation slide
- **notebooks:** identifying_duplicate_questions_quora.ipynb




