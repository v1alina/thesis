# Exploring ideas of accountability in AI regulation 

Master Thesis Project, Digital Humanities, Communication & Information Studies, Miriam Weigand
---
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
| ► corpus/oecd-ai-all-ai-policies.csv | [Original dataset from the OECD.AI](https://oecd.ai/en/dashboards/overview). Downloaded on the 02.05.2024 *OECD.AI. (2021). Database of national AI Policies [Dataset]. https://oecd.ai/en/dashboards/overview*|
| ► corpus/corpus_selection.csv | Narrowed down csv file containing possible selection of policy initiatives from the origial dataset. |
| ► corpus/cleaned_policies.csv | Final selection of all 87 AI frameworks. |
| ► corpus/paragraphs-all | Text file including the entirety of the corpus set. Each document is divided into paragraphs of 3 consecutive sentences. All parapgraps are seperated by `\n`.|
|EDA_all_policies.ipynb| Juypter Notebook going into exploratory data analysis and explaining the corpus selection process. Further, this notebook goes into the conversion from the downloaded frameworks as PDF files into text files for further processing. |
| BERTopic_v1.ipynb | Jupyter Notebook on the creation of a standard topic model, includes the preprocessing and visualisations of the topic model. *Unfortunately the saved model cannot be uploaded to GitHub as it is over 250mb.* |
| LEGAL_BERT_v2.ipynb | Jupyter Notebook on the creation of a fine-tuned topic model using [LEGAL-BERT embeddings](https://huggingface.co/nlpaueb/legal-bert-base-uncased). The notebook goes into some techinques for fine-tuning a BERTopic model. Further, topics of interests are visualised. *Unfortunately the saved model cannot be uploaded to GitHub as it is over 250mb.* |
