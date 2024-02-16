# Cross-Domain-Multi-Intent-Identification-in-Low-Resource-Languages
The project focuses on improving Natural Language Understanding (NLU) tasks for low-resource languages, particularly Bengali, within the Indian language context. It employs high-resource languages as pivot languages and explores methods like Retrieval-augmented Generation (RAG) and chunking for better context generation and understanding. The key contributions and findings include:

1) **Semantically Similar Pivot Language Identification:** Identifies Hindi as a pivot language for Bengali and explores semantic similarity through cosine similarity metrics using Wikipedia articles.
2) **RAG with Vector Database:** Utilizes a vector database to store embeddings of high-resource languages, facilitating faster retrieval and indexing for RAG in low-resource languages.
3) **Chunking and K-value Optimization:** Shows how segmenting user utterances and varying k-values improve context creation for multi-intent and cross-domain identification. It compares the performance of RAG with different k-values across segments.
4) **Model Comparisons and Experimentation:** Compares the performance of language models (LLMs) like GPT 3.5 Turbo and Llama2-13b for intent classification and identifies GPT 3.5 Turbo as superior.
5) **Result Analysis:** Demonstrates the effectiveness of chunking and varied k-values through experiments, highlighting improved accuracy and efficiency in NLU tasks for low-resource languages.
   
The future directions include expanding the methodology to other NLP tasks and exploring strategies for optimizing few-shot prompting in low-resource languages. The project aims to make NLU more inclusive and efficient for linguistic nuances in low-resource and underexplored languages.
