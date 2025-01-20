# StoryWriter

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Finetuning](#finetuning)
- [Results](#results)


## Introduction

The goal of this mini-project is to create a tool that generates bedtime stories based on user-provided input. The tool leverages a large dataset of short stories and fine-tunes a pre-trained language model to generate coherent and engaging stories tailored to the user's preferences. The project explores two distinct approaches: keyword-based and one-sentence summary-based story generation. Both approaches aim to create a flexible and user-friendly tool for generating personalized bedtime stories.  

## Dataset
The dataset used in this project is the TinyStories Narrative Classification Dataset, available on [Kaggle](https://www.kaggle.com/datasets/thedevastator/tinystories-narrative-classification/data). It contains 1.8 million short stories on various topics, making it an ideal resource for training a story-generation model.

### Datset preparation 

1. Keyword Extraction Using N-Grams:

2. One-Sentence Summaries:

   For the summary-based approach, each story in the dataset is summarized into a single sentence. These summaries were generated using the LLaMA 3.2 3B language model, ensuring high-quality and coherent summaries.

## Finetuning

The project involves fine-tuning the TinyLlama 1.1B model, a lightweight yet powerful language model, using a subset of the TinyStories dataset. To ensure efficient training, we will use 20,000 examples from the dataset for fine-tuning. 


## Results


