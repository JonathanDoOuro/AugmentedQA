# AugmentedQA

This project is part of a bigger project called QUizzing, which has as its objective to generate and answer questions to help students. The solution aims to serve a variety of areas of knowledge, such as history, biology, law and medicine. 

The foucous of this specific project is to develop a model that is capable of answering open domain questions. In order to do such thing, its used a techinique known as retrival augmented
generation.

In the first place its collected and stored a lot of text data related to the fields the model should have knowledge about, then given a question a search on the stored texts is done aiming
to retrive extra context to provide a large language model that is responsible to answer the question. 

