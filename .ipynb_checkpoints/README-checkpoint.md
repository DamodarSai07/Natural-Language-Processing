\## Natural Language Processing:



This repository consists of NLP course classes I learned in udemy through this course:



https://www.udemy.com/course/nlp-in-python-probability-models-statistics-text-analysis/learn/lecture/48343471?src=sac\&kw=NLP#overview

### 1. Learned about basic text splitting and basic text preprocessing techniques:

Preprocessing is crucial for all the works we do in machine learning. Preprocessing helps in checking, cleaning the data. Some of the preprocessing techniques we use in NLP are
1. Tokenization: In natural language processing we will process the text by using tokens. Token is nothing but a word or a special character present inside the text tokenization helps to break a sentence into some tokens.
2. Stemming: Stemming is the process where we preprocess the text into some machine understanding format which is root or base from which can be understood by machine but sometimes look like meaningless words or tokens for humans.
3. Lemmatizaton: Lemmatization is the process where we will preprocess the text into some machine and human understanding format like dictionary format words lemmatization is used over stemming because we cannot form meaningful sentences using root or base form words.

Steps we use to do basic preprocessing of text

Step - 1: Input: We take input in form of a sentence or a paragraph

Step - 2: Tokenization: We convert the input into tokens 

Step - 3: Stopword Removal: We remove some stopwords like ['a', 'an', 'be', 'do'] in this step

Step - 4: Case Conversion: We convert the all tokens into same case mostly lowercase().

Step - 5: Stemming/Lemmatization: We Perform stemming or lemmatization (mostly lemmatization) to word to get machine and human understandable text.