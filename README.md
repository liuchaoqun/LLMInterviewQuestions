# 100+ LLM Interview Questions for Top Companies

This repository contains over 100 interview questions for Large Language Models (LLM) used by top companies like Google, NVIDIA, Meta, Microsoft, and Fortune 500 companies. Explore questions curated with insights from real-world scenarios, organized into 14 categories to facilitate learning and preparation.

---

## Table of Contents

1. [Prompt Engineering & Basics of LLM](#prompt-engineering--basics-of-llm)
2. [Retrieval Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
3. [Chunking Strategies](#chunking-strategies)
4. [Embedding Models](#embedding-models)
5. [Internal Working of Vector Databases](#internal-working-of-vector-databases)
6. [Advanced Search Algorithms](#advanced-search-algorithms)
7. [Language Models Internal Working](#language-models-internal-working)
8. [Supervised Fine-Tuning of LLM](#supervised-fine-tuning-of-llm)
9. [Preference Alignment (RLHF/DPO)](#preference-alignment-rlhfdpo)
10. [Evaluation of LLM System](#evaluation-of-llm-system)
11. [Hallucination Control Techniques](#hallucination-control-techniques)
12. [Deployment of LLM](#deployment-of-llm)
13. [Agent-Based System](#agent-based-system)
14. [Prompt Hacking](#prompt-hacking)
15. [Case Study & Scenario-Based Questions](#case-study--scenario-based-questions)

---

## Prompt Engineering & Basics of LLM

- **What is the difference between Predictive/Discriminative AI and Generative AI?**
- **What is LLM, and how are LLMs trained?**
- **What is a token in the language model?**
- **How to estimate the cost of running SaaS-based and Open Source LLM models?**
- **Explain the Temperature parameter and how to set it.**
- **What are different decoding strategies for picking output tokens?**
- **What are different ways you can define stopping criteria in large language model?**
- **How to use stop sequences in LLMs?**
- **Explain the basic structure prompt engineering.**
- **Explain in-context learning**
- **Explain type of prompt engineering**
- **What are some of the aspect to keep in mind while using few-shots prompting?**
- **What are certain strategies to write good prompt?**
- **What is hallucination, and how can it be controlled using prompt engineering?**
- **How to improve the reasoning ability of LLM through prompt engineering?**
- **How to improve LLM reasoning if your COT prompt fails?**

[Back to Top](#table-of-contents)

---

## Retrieval Augmented Generation (RAG)

- **how to increase accuracy, and reliability & make answers verifiable in LLM**
- **How does RAG work?**
- **What are some benefits of using the RAG system?**
- **When should I use Fine-tuning instead of RAG?**
- **What are the architecture patterns for customizing LLM with proprietary data?**

[Back to Top](#table-of-contents)

---

## Chunking Strategies

- **What is chunking, and why do we chunk our data?**
- **What factors influence chunk size?**
- **What are the different types of chunking methods?**
- **How to find the ideal chunk size?**

[Back to Top](#table-of-contents)

---

## Embedding Models

- **What are vector embeddings, and what is an embedding model?**
- **How is an embedding model used in the context of LLM applications?**
- **What is the difference between embedding short and long content?**
- **How to benchmark embedding models on your data?**
- **Suppose you are working with an open AI embedding model, after benchmarking accuracy is coming low, how would you further improve the accuracy of embedding the search model?**
- **Walk me through steps of improving sentence transformer model used for embedding?**

[Back to Top](#table-of-contents)

---

## Internal Working of Vector Databases

- **What is a vector database?**
- **How does a vector database differ from traditional databases?**
- **How does a vector database work?**
- **Explain difference between vector index, vector DB & vector plugins?**
- **You are working on a project that involves a small dataset of customer reviews. Your task is to find similar reviews in the dataset. The priority is to achieve perfect accuracy in finding the most similar reviews, and the speed of the search is not a primary concern. Which search strategy would you choose and why?**
- **Explain vector search strategies like clustering and Locality-Sensitive Hashing.**
- **How does clustering reduce search space? When does it fail and how can we mitigate these failures?**
- **Explain Random projection index?**
- **Explain Locality-sensitive hashing (LHS) indexing method?**
- **Explain product quantization (PQ) indexing method?**
- **Compare different Vector index and given a scenario, which vector index you would use for a project?**
- **How would you decide ideal search similarity metrics for the use case?**
- **Explain different types and challenges associated with filtering in vector DB?**
- **How to decide the best vector database for your needs?**

[Back to Top](#table-of-contents)

---

## Advanced Search Algorithms

- **What are architecture patterns for information retrieval & semantic search?**
- **Why it’s important to have very good search**
- **How can you achieve efficient and accurate search results in large-scale datasets?**
- **Consider a scenario where a client has already built a RAG-based system that is not giving accurate results, upon investigation you find out that the retrieval system is not accurate, what steps you will take to improve it?**
- **Explain the keyword-based retrieval method**
- **How to fine-tune re-ranking models?**
- **Explain most common metric used in information retrieval and when it fails?**
- **If you were to create an algorithm for a Quora-like question-answering system, with the objective of ensuring users find the most pertinent answers as quickly as possible, which evaluation metric would you choose to assess the effectiveness of your system?**
- **I have a recommendation system, which metric should I use to evaluate the system?**
- **Compare different information retrieval metrics and which one to use when?**
- **How does hybrid search works?**
- **If you have search results from multiple methods, how would you merge and homogenize the rankings into a single result set?**
- **How to handle multi-hop/multifaceted queries?**
- **What are different techniques to be used to improved retrieval?**
  

[Back to Top](#table-of-contents)

---

## Language Models Internal Working

- **Detailed explanation of Transformer architecture and self-attention.**
- **Advantages of using a transformer over LSTM.**
- **How to increase the context length of an LLM?**
- **What is a mixture of expert models?**

[Back to Top](#table-of-contents)

---

## Supervised Fine-Tuning of LLM

- **What is fine-tuning, and why is it needed?**
- **How to create fine-tuning datasets for Q&A?**
- **What are different re-parameterized methods for fine-tuning?**
- **What is catastrophic forgetting in LLMs?**

[Back to Top](#table-of-contents)

---

## Preference Alignment (RLHF/DPO)

- **What is RLHF, and how is it used?**
- **Explain different preference alignment methods.**
- **What is the reward hacking issue in RLHF?**

[Back to Top](#table-of-contents)

---

## Evaluation of LLM System

- **How to evaluate RAG-based systems?**
- **What are different metrics for evaluating LLMs?**

[Back to Top](#table-of-contents)

---

## Hallucination Control Techniques

- **What are different forms of hallucinations?**
- **How to control hallucinations at various levels?**

[Back to Top](#table-of-contents)

---

## Deployment of LLM

- **Why does quantization not decrease the accuracy of LLM?**

[Back to Top](#table-of-contents)

---

## Agent-Based System

- **What are agents, and why are they needed?**
- **Explain ReAct prompting with examples.**
- **Difference between OpenAI functions and LangChain agents.**

[Back to Top](#table-of-contents)

---

## Prompt Hacking

- **What is prompt hacking, and why is it important?**
- **What are the different defense tactics against prompt hacking?**

[Back to Top](#table-of-contents)

---

## Case Study & Scenario-Based Questions

- **How to optimize the cost of an overall LLM system?**

[Back to Top](#table-of-contents)

---

*For more resources, visit [Mastering LLM](https://www.masteringllm.com).*
