# AugmentedQA

This project is part of a bigger project called Quizzing, which has as its objective to generate and answer academic questions with updated content. The solution aims to serve a variety of areas of knowledge, such as history, biology, law and medicine.

The focus of this specific project is to develop a model that is capable of answering open domain questions. In order to do such thing, it's used a technique known as retrieval augmented generation.

In the first place it's collected and stored a lot of text data related to the areas of knowledge we cover, then given a question a search on the stored texts is done aiming to retrieve extra context to provide a large language model that is responsible to answer the question.

CURRENT STATE:

At the time, I am building the retriever using ChromaDb. The retriever gets the 10 most relevant documents to answer a question. This retriever needs to use embeddings in order to perform semantic search, so I'm doing experiments to find the best embedding model that suits texts in Portuguese. The retriever also makes use of name entity recognition, it searches the entities in the text corpus to find relevant documents that might have the answer to the question made.


