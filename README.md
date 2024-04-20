# NLP Sentence Classification Report

## Overview
This project investigates various Natural Language Processing (NLP) methods for classifying sentences into 12 distinct categories using Large Language Models (LLMs), fine-tuned BERT, DistilBERT and SetFit. We employ data augmentation techniques to overcome challenges posed by a limited training dataset.

## Key Findings
- All explored methods achieved over 80% accuracy on the test dataset.
- The SetFit model outperformed other approaches.

## Techniques Used
1. **Large Language Models (LLMs):** Utilized models like Llama3 in zero-shot and few-shot learning contexts.
2. **BERT:** Fine-tuned the BERT model with augmented datasets to enhance classification performance.
3. **DistilBERT:** Fine-Tuned the DistilBERT model with augmented datasets to enhance classification performance.
4. **SetFit:** Employed for superior performance in sentence classification tasks.
5. **Data Augmentation:** Used `nlpaug` for synonym substitution and back translation, and employed ChatGPT to generate similar sentences, effectively expanding our dataset.

## Data Augmentation Details
- Synonym substitution and back translation to/from Chinese to expand dataset variety.
- ChatGPT-generated sentences to enhance training data diversity.

## Results
- SetFit achieved the highest accuracy of 86%.
- Fine-tuned BERT with ChatGPT-augmented data reached 82% accuracy.
- Fine-tuned DistilBERT with ChatGPT-augmented data reached 81% accuracy.
- LLMs showed robust performance with accuracies ranging from 77% to 80%.





