# PersianPoetVec
PersianPoetVec: A Word2Vec model trained on the complete works of Saadi, Hafez, and Rumi (Masnavi and Diwan-e Shams). Using Gensim, this project creates embeddings that capture the unique semantics of classical Persian poetry, allowing for insightful comparisons with Google’s 2013 Word2Vec model.

# Poetry Word2Vec Embeddings

This project aims to create word embeddings specifically for Persian poetry, using the works of Saadi, Hafez, and Rumi. The Word2Vec model is used to generate vector representations for words in the corpus. Additionally, you can compare the embeddings with pre-trained Word2Vec models, such as Google's pre-trained model for English.

## How to Use

### Step 1: Download Pre-trained Word2Vec Model

To compare the embeddings generated by this model with the ones trained on the Google News dataset, you can download the pre-trained Word2Vec embeddings from Google's official archive.

1. Visit [Google's Word2Vec archive](https://code.google.com/archive/p/word2vec/).
2. Download the **GoogleNews-vectors-negative300.bin** file from the "Pre-trained word and phrase vectors" section.
3. Once downloaded, place the file into the `Model` directory of this repository.

### Step 2: Set Up the Environment

Before running the project, make sure you have the necessary libraries installed. You can use `pip` to install the required dependencies:

