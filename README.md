# Spam Detection using Transformers

This project demonstrates a basic spam detection system using **Transformers** (BERT) for text classification.

## Overview

The goal of this project is to classify emails as **spam** or **ham** using a pretrained BERT model. The process involves:

1. **Loading a pretrained BERT model** for sequence classification.
2. **Tokenizing the emails** into input IDs and attention masks.
3. **Running inference** using the model to predict if an email is spam or not.

## Notes

- While this project uses Transformers, it is important to note that **spam detection can also be done using simpler machine learning algorithms** such as logistic regression, decision trees, or Naive Bayes.  
- Using traditional ML methods could have **saved a lot of time and computation**, especially for smaller datasets.  
- The purpose of this project is to **understand the workflow of Transformers** for text classification and see how BERT processes text to make predictions.  

## Conclusion

This is a basic example to get familiar with **Transformers for NLP tasks**. For production-level spam detection, traditional ML or optimized deep learning pipelines may be more practical.
