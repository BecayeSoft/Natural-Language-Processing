# Natural-Language-Processing
The sorcery of Natural Language processing form basic techniques such as Word2Vec, Topic Modelling to LSTMs and pre-trained transformers.

If you have any questions or suggestions, don't hesitate to reach out!

## Requirement

```
pip install -r requirement.txt
```

## Table of Contents

### 1. [Basics](#basics)

This section covers the fundamentals of natural language processing (NLP). It introduces Spacy, a powerful NLP library, and covers topics like tokenization, lemmatization, stopword removal, and pattern matching.

   - [Spacy Intro](1.%20Basics/1.%20Spacy%20Intro.ipynb)
   - [Tokenization](1.%20Basics/2.%20Tokenization.ipynb)
   - [Lemmetization](1.%20Basics/3.%20Lemmetization.ipynb)
   - [Stopwords](1.%20Basics/4.%20Stopwords.ipynb)
   - [Pattern Matching](1.%20Basics/5.%20Pattern%20Matching.ipynb)
   - [Assignment](1.%20Basics/Assignement.ipynb)
   - [Spacy Visualizers](1.%20Basics/Spacy%20Visualizers.ipynb)

###  2. [POS and NER](#pos-and-ner)
   
This section focuses on Part-of-Speech (POS) tagging and Named Entity Recognition (NER). It explores how to assign POS tags to words in a sentence and how to identify and classify named entities like names, locations, and organizations.

   - [POS Tagging](2.%20POS%20and%20NER/1.%20POS%20Tagging.ipynb)
   - [Named Entity Recognition](2.%20POS%20and%20NER/2.%20Named%20Entity%20Recognition.ipynb)
   - [ERROR 3. Sentence Segmentation](2.%20POS%20and%20NER/ERROR%203.%20Sentence%20Segmentation.ipynb)
   - [Visualizing NER](2.%20POS%20and%20NER/Visualizing%20NER.ipynb)
   - [Visualizing POS](2.%20POS%20and%20NER/Visualizing%20POS.ipynb)

### 3. [Text Classification](#text-classification)

Text classification is the task of assigning predefined categories or labels to text data. This section demonstrates how to build a text classifier to detect spam messages using machine learning techniques.

   - [Spam Detection](3.%20Text-classification/Spam%20detection.ipynb)
   - [Dataset: sms_spam.csv](3.%20Text-classification/sms_spam.csv)

### 4. [Word2Vec](#word2vec)

Word2Vec is a popular word embedding technique that represents words as numerical vectors. This section delves into unsupervised sentiment analysis and how to create word embeddings using the Word2Vec model.
   - [Unsupervised Sentiment Analysis](4.%20Word2Vec/Unsuppervised%20Sentiment%20Analysis.ipynb)
   - [Word2Vec](4.%20Word2Vec/Word2Vec.ipynb)

### 5. [Topic Modeling](#topic-modelling)

Topic modeling is a technique used to discover hidden thematic patterns in a collection of documents. This section explores Latent Dirichlet Allocation (LDA), a popular topic modeling algorithm.

   - [Latent Dirichlet Allocation](5.%20Topic%20Modelling/Latent%20Dirichlet%20Allocation.ipynb)

### 6. [Text Generation](#text-generation)

Text generation involves creating new text based on existing patterns. This section demonstrates how to generate text using Long Short-Term Memory (LSTM) neural networks and provides resources for text generation from the novel "Moby Dick."

   - [Text Generation with LSTM](6.%20Text%20Generation/Text%20Generation%20with%20LSTM.ipynb)
   - [moby_dick_four_chapters.txt](6.%20Text%20Generation/moby_dick_four_chapters.txt)
   - Models: Saved models.
     - [mobydick_4_chapters_model.h5](6.%20Text%20Generation/models/mobydick_4_chapters_model.h5)
     - [mobydick_4_chapters_tokenizer](6.%20Text%20Generation/models/mobydick_4_chapters_tokenizer)
     - [mobydick_all_chapters_model.h5](6.%20Text%20Generation/models/mobydick_all_chapters_model.h5)
     - [mobydick_all_chapters_tokenizer](6.%20Text%20Generation/models/mobydick_all_chapters_tokenizer)
