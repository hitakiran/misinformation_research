# Uncovering Themes in Junk Science Articles with BERTopic

This repository explores themes in junk science news articles using BERTopic, a transformer-based topic modeling library. The goal is to uncover different **junk science topics** across thousands of articles that are labeled as junk science.

---

## Repository Contents

- **`junksci_topic_model.ipynb`**  
  Jupyter notebook containing the full pipeline: data loading, text preprocessing, BERTopic model training, topic inspection, and topic labeling for the junk science corpus.

- **`junk_sci_articles.csv`**  
  Processed dataset of junk science articles, including metadata and a `content` column that is used as input to BERTopic.

- **`.DS_Store`**  
  macOS-generated file that can be ignored. 

---

## Install Dependencies

Install **BERTopic** and core libraries (exact versions may vary):

pip install bertopic pandas scikit-learn nltk


The notebook uses the following imports:

- import pandas as pd

- from bertopic import BERTopic # topic modeling

- from sklearn.feature_extraction.text import TfidfVectorizer

- from sklearn.feature_extraction import text

- import re

- import string

- from nltk.stem import WordNetLemmatizer

To use WordNetLemmatizer, download the required NLTK resources:

- import nltk
  
- nltk.download("wordnet")
  
- nltk.download("omw-1.4")
  

---

## Resources Used

These resources were used to learn and apply BERTopic:

- Nicholas Renotte – **BERTopic Tutorial (YouTube)**:  
https://www.youtube.com/watch?v=v3SePt3fr9g  

- **BERTopic Workflow Tutorial (YouTube)**:  
https://www.youtube.com/watch?v=-_-nqJ9Bzk8  

- Maarten Grootendorst – **BERTopic Documentation**:  
https://maartengr.github.io/BERTopic/index.html  

- Stackademic – **“Topic Modelling with BERTopic”**:  
https://blog.stackademic.com/topic-modelling-with-bertopic-249095144555  

- Maarten Grootendorst – **BERTopic GitHub Repository**:  
https://github.com/MaartenGr/BERTopic







