# Embedding Vectors

This directory is to introduce different methods of vectorizing and embedding vocabulary to use in machine learning methods. It first starts with sparse methods like term frequency, TF-IFD, and PPMI methods, then continues with dense vectors like GloVE. The notebook also contains an adequate implementation of skipgram model.

## Data

Unfortunately the provided piece of code doesn't download the required data automatically. This is due to unfortunate sanctions and restrictions against Iranian users. Here's a list of links that you need to download their material:
- For Q1: (Sentiment140)[https://www.kaggle.com/datasets/kazanova/sentiment140]
- For Q2: (GloVE)[https://nlp.stanford.edu/data/glove.6B.zip]. Extract the zip file and put the 50d in the `assets` directory.
- For Q3: (Sherlock Holmes Stories Text)[https://sherlock-holm.es/stories/plain-text/advs.txt]
- There is also a `sarcasm.json` already available which was provided by the teaching staff.