### Chatbot And RAG Evaluation

Retrieval Augmented Generation (RAG) is a technique that enhances Large Language Models (LLMs) by providing them with relevant external knowledge. It has become one of the most widely used approaches for building LLM applications.

This tutorial will show you how to evaluate your RAG applications using LangSmith. You'll learn:

1. How to create test datasets
2. How to run your RAG application on those datasets
3. How to measure your application's performance using different evaluation metrics

#### Overview
A typical RAG evaluation workflow consists of three main steps:

1. Creating a dataset with questions and their expected answers
2. Running your RAG application on those questions
3. Using evaluators to measure how well your application performed, looking at factors like:
 - Answer relevance
 - Answer accuracy
 - Retrieval quality
 
For this tutorial, we'll create and evaluate a bot that answers questions about a few of Lilian Weng's insightful blog posts.



## 1) Gathering Data Points
## 2) LLM as a Judge + Prompt
## 3) Evaluation Metrics
## 4) Comparison between LLM models and will select the best model

LangSmith is used here for entire tracking of the process in the Langsmith platform