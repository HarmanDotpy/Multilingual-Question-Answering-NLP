# Multilingual-Question-Answering-NLP
Multilingual QnA - Submission to Chaii (Challenge in AI for India) competition on Kaggle

Goal was to train a model to for the task of question answering over 2 Indain Languages, Hindi and Tamil. It is used for submission in a Kaggle competition, [chaii - Hindi and Tamil Question Answering](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/overview), by **Google Research India** to improve the performance of NLU models in Indian languages (which are generally low resource languages).
Given a context and question, the goal of question answering is to predict the answer to the question by selecting a span from the context.

## Following is our modelling choices
### Model

[XLM-RoBERTa-large finetuned on Squad v2](https://huggingface.co/deepset/xlm-roberta-large-squad2)

### Datasets

1. [Chaii-1](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/overview) question answering dataset (has Hindi and Tamil QnA pairs). 
3. [MLQA](https://www.kaggle.com/rhtsingh/external-data-mlqa-xquad-preprocessing) (MultiLingual Question Answering) released by [Facebook Research](https://github.com/facebookresearch/MLQA)

### Authors

- [Harman Singh](https://github.com/HarmanDotpy)
- [Rocktim Jyoti Das](https://github.com/RocktimJyotiDas)

Kaggle team name: Rock-The-Tim

Work done as part of the [NLP Course Assignment](https://www.cse.iitd.ac.in/~mausam/courses/col772/autumn2021/A4/A4.pdf) by [Prof. Mausam](https://www.cse.iitd.ac.in/~mausam/)
