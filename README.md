# Exploring ideas of accountability in AI regulation (Master Thesis Project 2024)

My master thesis project on accountability in AI regulation. The thesis explore the use of topic modeling to find associated words and passages related to *accountability* in a corpus of AI regulatory frameworks.


## View notebooks and topic model visualisations
View the topic models with their interactive graphs via the NBviewer:

- [BERTopic_v1](https://nbviewer.org/github/v1alina/thesis/blob/main/BERTopic_v1.ipynb)
- [LEGAL_BERT_v2](https://nbviewer.org/github/v1alina/thesis/blob/main/LEGAL_BERT_v2.ipynb)


## Contents

This repository contains details on the curation of the data set, the preprocessing, and the creation of two seperate topic models.


| File | Description |
| -----------| -----------|
| corpus | folder containing 3 csv files and all the corpus data in a text file seperated into parapgraphs |
| ► corpus/oecd-ai-all-ai-policies.csv | [original dataset from the OECD.AI](https://oecd.ai/en/dashboards/overview), downloaded on the 02.05.2024 (OECD.AI. (2021). Database of national AI Policies [Dataset]. https://oecd.ai/en/dashboards/overview
)|
| BERTopic_v1 | Jupyter Notebook on the creation of a standard topic model, includes the preprocessing and visualisations of the topic model. Unfortunately the saved model cannot be uploaded as it is over 250mb|
| LEGAL_BERT_v2
