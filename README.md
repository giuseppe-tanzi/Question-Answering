<a target="_blank" href="https://colab.research.google.com/github/giuseppe-tanzi/Question-Answering/blob/main/Question_Answering.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Question-Answering

Authors:
- [Yuri Noviello](https://github.com/yurinoviello)
- [Enrico Pallotta](https://github.com/PallottaEnrico)
- [Flavio Pinzarrone](https://github.com/flaviopinzarrone)
- [Giuseppe Tanzi](https://github.com/giuseppe-tanzi)

## Abstract 

Conversational question answering is a task in natural language processing where the goal is to generate a natural language response to a question based on a given context and previous conversation history. Transformer-based models have recently shown promise in this task due to their ability to handle long-range dependencies and encode rich contextual information. In this report we present results on the task achieved using seq2seq transformer-based models with DistilRoBERTa and BERT-tiny, fine-tuned on the CoQA dataset.

## Dataset

[CoQA](https://stanfordnlp.github.io/coqa/) is a large-scale dataset for building Conversational Question Answering systems. CoQA contains 127,000+ questions with answers collected from 8000+ conversations. Each conversation is collected by pairing two crowdworkers to chat about a passage in the form of questions and answers. The unique features of CoQA include:
- the questions are conversational; 
- the answers can be free-form text; 
- each answer also comes with an evidence subsequence highlighted in the passage; 
- the passages are collected from seven diverse domains. 

## Resources and references
- [Pytorch](https://pytorch.org/)
- [HuggingFace](https://huggingface.co/)
- [CoQA dataset](https://stanfordnlp.github.io/coqa/)


