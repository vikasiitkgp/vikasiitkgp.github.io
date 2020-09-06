---
toc: true
layout: post
description: NLP tasks and learning materials
categories: [nlp]
image: images/nlp_title.png
title: Overview of NLP
---

This first post provides the overview of Natural Language Processing (NLP).

### What is NLP:

Natural language processing (NLP) is the field of Artificial Intelligence that gives machine the ability to read, understand & derive meaning from Human language. 
Simply put, it allows computers to understand human language — speech or text.



### Significance of NLP
> NLP is the most important field of Machine learning. CEO, [Huggingface](https://huggingface.co/)

There has been paradigm shift in the field of NLP. Based on a [research](https://www.prnewswire.com/news-releases/global-natural-language-processing-nlp-market-set-to-reach-26-4-billion-by-2024--rising-at-a-cagr-of-21-from-2019--300976936.html), this industry is expected to grow from USD 10.2 billion in 2019 to USD 26.4 billion by 2024. 

NLP involves mining unstructured text data. According to IBM, around 80% of all available information is unstructured, with text being one of the most common types of unstructured data. Natural Langauge Processing (NLP) can be leveraged 
to analyze, understand and automate wide variety of tasks.

### Different tasks in NLP 
- **Text Classification:** *It is the process of categorizing texts in predefined category.You can use tf-idf vectorizer and transfer learning based approach (BERT) to classify text. Here are some of the examples.*

  Sentiment Analysis: It provides overall sentiments (positive / Neutral / Negative) of the blocks of texts (e.g movies or product reviews).

  ![]({{ site.baseurl }}/images/intro_nlp/sentiment_analysis.png "Reference: https://monkeylearn.com/sentiment-analysis/")

  Spam Detection: Email or SMS is categorized as spam or not. The contents of the email / SMS is passed through Classifier that predicts the probability of spam.
    ![]({{ site.baseurl }}/images/intro_nlp/spam_detection.png "Reference: https://medium.com/@naveeen.kumar.k/naive-bayes-spam-detection-7d087cc96d9d")

  *other classification tasks are Language detection, product categorization etc.*


- **Name Entity Recognition (NER):** *It is a technique used in information extraction to identify and segment the  named entities and classify or categorize them under various predefined classes like person names, organizations,time,locations.In this task, each of the token of sentence is classified into a category*
*Open-Source libraries widely used for NER: [NLTK](https://www.nltk.org/), [SpaCy](https://spacy.io/), [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) and [FlairNLP](https://github.com/flairNLP/flair).* 

    Here is example of NER using Spacy:
   ![]({{ site.baseurl }}/images/intro_nlp/ner.png "Reference: https://spacy.io/")

- **Machine Translation:** *It is a process of translating text of one language to another without human involvement (for example- Chinese to English). A seq of words from a language are converted into another sequence of words using (encoder - decoder )sequence to sequence architecture.*

   ![]({{ site.baseurl }}/images/intro_nlp/nmt-model-fast.gif "Reference: https://google.github.io/seq2seq/")

- **Information Retrieval:** *It facilitates the searach of relevant documents from collection of documents for a query and returns the sorted relevant data. [ElasticSearch](https://www.elastic.co/) can be used to index the documents and retrieve the most relevant docs on the basic of similarity. The documents feature is created by classical approach (TF-IDF) or deep learning based techniques like BERT to create features*

![]({{ site.baseurl }}/images/intro_nlp/info_retrieval.jpg "Reference: https://www.analyticsvidhya.com/blog/2015/04/information-retrieval-system-explained/")

- **Question Answer System:** *The basic idea of this system is to extracct the relevant answer from passage for a given question. Various Deep leaarning based architecture like RNN & Transformer achieves state of the art results of question answer tasks.*

![]({{ site.baseurl }}/images/intro_nlp/qa.png "Reference: https://rajpurkar.github.io/SQuAD-explorer/")

- **Language Model:** *It provides the probabibilty of sentence or probabality of next word given previous words.It is used to generate the text and it is also the foundation of state of the art results for different NLP tasks. It is leveraged by pre-training before downstream tasks. Here is a example of recent language model
 from OpenAI.*

 ![]({{ site.baseurl }}/images/intro_nlp/lm.gif "Reference: OpenAI")


### Resources for NLP

- *Reference MOOC Course / Tutorials:*
    - [NLP by Standford University](https://www.youtube.com/playlist?list=PLLssT5z_DsK8HbD2sPcUIDfQ7zmBarMYv) 
    - [fastai- Intro to NLP](https://www.youtube.com/playlist?list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9)
    - [Standford CS224n: NLP with deep learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&fbclid=IwAR1R3-VyCBrF1hCZGrhOmk24XMjGkHe27U8wMDp8oQ6XPViWd1DzEgH4Qp4)
 
-  *Blogs & Posts:*
    - [Sebastian Ruder's NLP Blog](https://ruder.io/tag/natural-language-processing/)
    - [Papers with Code](https://paperswithcode.com/area/natural-language-processing)
    - [Made with ML](https://madewithml.com/topics/natural-language-processing/)


