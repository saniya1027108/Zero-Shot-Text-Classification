# Zero-Shot-Text-Classification

### A Complete Descriptive Blog on Zero Shot Classification - [Click Here](https://medium.com/@saniyamulla108/zero-shot-learning-in-natural-language-processing-7c69cdd1af55)

Zero-shot learning (ZSL) most often referred to a fairly specific type of task: learn a classifier on one set of labels and then evaluate on a different set of labels that the classifier has never seen before.

This approach is used for finding out the probabilistic classififcation of any resume, with the categories being : 
 - AI
 - Web developer
 - Big data
 - Enterprise
 - UI UX
 - Cloud developer
 - Finance
 - Human Resource
 - Database
 - Sales
 - Mobile app Developer
 - Customer management
 - Admin
 - Legal
 - Business Analyst
 - Writing
 - Engineering
 
This will help to identify the resume belongs to which of the following categories by predicting a probability score.
A `Transformers Hugging Face` model has been used.

## Dataset:
The testing dataset consists of around 100 resumes (string format) in a csv file. 

## Preprocessing Steps used:
 - Removing Whitespaces, URLS, gmails, hashtags and phone numbers.
 - Stop word removal (library - NLTK)

## References:
[Zero-Shot Text Classification with Hugging Face](https://towardsdatascience.com/zero-shot-text-classification-with-hugging-face-7f533ba83cd6)

[Semantic Textual Similarity with BERT](https://towardsdatascience.com/semantic-textual-similarity-with-bert-fc800656e7a3)

[Zero Shot Learning Model in NLP](https://joeddav.github.io/blog/2020/05/29/ZSL.html)

