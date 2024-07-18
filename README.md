# NLP Course Projects

This repository contains six computer assignment of the NLP course at the University of Tehran. The course was based on the "Speech and Language Processing" book by Jurafski and H. Martin, which you can find it [here](https://web.stanford.edu/~jurafsky/slp3/). Here is a short description of each:

## 1. Tokenization and N-Grams

This project contains a look into different tokenization algorithms and an implementation of BPE and SentencePiece algorithms. There is also an implementation of a simple language model using n-grams.

## 2. Embedding Vectors

This one implements several sparse and dense vectorization algorithms like tf-idf, ppmi, and skipgram.

## 3. Semantic Role Labeling

This project tries to do the task of SRL using a small dataset and three kinds of neural networks.

## 4. Fine Tuning

We take a look into LoRA and QLoRA along other methods of fine tuning called ICL. These are all performed over Llama and Roberta language models to do a task of sentence entailment, using the MultiNLI dataset.

## 5. Machine Translation

Implementing a translation tool using `fairseq` tools and [Mizan](https://github.com/omidkashefi/Mizan) dataset.

## 6. Chat Bots

This project is an implementation of chat bot capable of answering user questions about NLP and Speech Recognition, using the Jurafsky's text book. It uses LangChain to implement different parts of the bot including retrievers, search engine, and text generation.
