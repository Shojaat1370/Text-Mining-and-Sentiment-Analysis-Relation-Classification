# Text-Mining-and-Sentiment-Analysis-Relation-Classification
This is a project for Text mining and sentiment analysis course. Topic was Relation Classification using Deep Learning Techniques and Knowledge Graph

## Relation Classification using LSTM and BERT Models and leveraging Knowledge Graph 

## Overview:

Relation classification is a critical task in natural language processing (NLP) that focuses on identifying semantic relationships between entities in text. 
This project investigates the application of Long Short-Term Memory (LSTM) networks with a bi-directional architecture and the Bidirectional Encoder Representations from Transformers (BERT) model, utilizing different hyperparameters for relation classification. Additionally, Knowledge Graph (KG) techniques are employed to represent the relation between subjects and objects in the provided texts.


## Objectives 

1. Investigate the performance of LSTM and bi-directional LSTM models in relation classification. 
2. Evaluate the effectiveness of BERT models with different layers in the same task.  
3. Compare and analyze the results to understand the potential and limitations of both approaches. 
4. Using Knowledge Graph (KG) techniques to represent the relation between subjects and objects by using provided predicates. 

## Dataset Link:  
https://code.google.com/archive/p/relation-extraction-corpus/downloads 

## Results:
The hyperparameter tuning and performance evaluation of LSTM, BiLSTM, BERT, and BERT_Large models for relation classification revealed key insights. BiLSTM performed best with a learning rate of 0.001 and a hidden dimension of 256, achieving an F1-Score of 0.81. BERT_Large excelled with an F1-Score of 0.89 at a lower learning rate of 0.00001 and 5 epochs. Higher learning rates consistently resulted in poor performance across all models, highlighting the importance of proper learning rate selection. 

BERT and BERT_Large models outperformed LSTM models due to their transformer architecture, which captures complex contextual relationships more effectively. These models required lower learning rates and showed greater sensitivity to epoch adjustments. 
