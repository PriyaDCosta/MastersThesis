# Introduction
   
Text augmentation, the process of expanding and diversifying a dataset, is crucial for enhancing the performance and generalization capabilities of models in various NLP applications.In recent years, Language Models (LMs) powered by Artificial Intelligence (AI), such as OpenAI's GPT-3, have revolutionized natural language processing tasks. Such LLMs offer immense potential for text augmentation.

There are many research works on text augmentation,which primarily center around different methods of text augmentation and their impact on text classification tasks. However, only one of these works, (Dai, Haixing, et al. "Chataug: Leveraging chat gpt for text data augmentation." arXiv preprint arXiv:2302.13007 (2023)) focuses on using a popular Large Language Model (LLM), i.e Chat GPT for augmenting text data. This paper only studies text augmentation using Chat GPT, and primarily uses data from the medical field to test the model.

Text augmentation using LLMs is highly dependent on the context of the data, and must be studied separately. Currently, there is no work that studies text augmentation by LLMs in different contexts. Text data is an important input to Computational Social Science, and future works in the space will be influenced by LLMs.

# Further Steps

We propose a model that will use different LLMs, namely GPT, Conditional Transformer Language Model (CTRL), T5 (Text-to-Text Transfer Transformer)(Not an exhaustive list and may change depending on accessibility of these models) 

This model will use LLMs to perform text augmentation on various data sets, such as sarcastic texts,question, opinion-based data and creative writing pieces (not an exhaustive list). We will then evaluate the semantic similarity of the the original text and the augmented text using metrics like cosine similarity, The final output is intended to be a comparison of how well different LLMs fare in different text augmentation tasks across different contexts.

# Research Questions

## RQ1
## RQ2

# Proposed Methodology (Just Intended Guidelines)

## Data
### [Sarcastic Data](https://www.kaggle.com/datasets/sherinclaudia/sarcastic-comments-on-reddit)
### Factual Data and Technical Data
### [Data With Varied Emotions (Customer Reviews)](https://www.kaggle.com/datasets/vigneshwarsofficial/reviews)
### [Data in the form of questions](https://www.kaggle.com/competitions/quora-insincere-questions-classification/data)
### [Opinion Based Data](https://www.kaggle.com/datasets/miroslavsabo/young-people-survey)
### [Conversations Data](https://www.kaggle.com/datasets/gogogaurav95/conversation-meetings)

## LLMs used
### Chat GPT
### XLNet
### DyloGPT
### BlenderBot
### Bard

## Text Augmentation Techniques
### Paraphrasing
### Backtranslation
### Synonym Replacement
### Alternative Spellings
### Sequence Alteration

## Drawing Inferences (Techniques to Compare Similarities Across Data Types)
### Cosine Similarity
### Dice's Coefficient
### Manhattan Distance
### Jaccard Distance
### Overlap Coefficient

# Intended Publication

Journal of Big Data: https://journalofbigdata.springeropen.com/about?gclid=Cj0KCQjwtO-kBhDIARIsAL6LoreoKKime2jQw6ywZ1qPJRIJDfSbK3nXOORzRwvp9r5b1YhR3NvAHnMaAr4qEALw_wcB 



