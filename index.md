---
layout: default
---

# DSC 180A Methodology Assignment 4

**Name:** Turki Alrasheed  
**Email:** talrasheed@ucsd.edu  
**Domain:** D28 - Epistemic Engines: Turning Raw Data into Living Knowledge Bases for AI Agents  
**Mentor:** Ryan Lingo

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me has been how we can transform raw, unstructured data into knowledge that AI systems can retrieve and reason over. In our DataMap project, I've been particularly interested in comparing different retrieval approaches, including keyword search, vector embeddings, and LLM-based search. It's interesting how the way information is represented and retrieved can significantly affect whether a system finds the right information, even when that information exists in its knowledge base.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate whether hybrid retrieval methods can improve natural-language dataset discovery compared to individual retrieval approaches. Specifically, I would compare keyword search, semantic search, and a hybrid method that combines both, using datasets with different levels of documentation quality. I would evaluate the methods using metrics such as Recall@k, MRR, and nDCG, while also considering latency and computational cost. The goal would be to identify which retrieval strategies work best for different types of user queries.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is to expand our evaluation beyond whether a system retrieves the correct dataset. I would like to analyze why certain retrieval methods fail, particularly for ambiguous queries or datasets with limited metadata. This could involve categorizing queries by difficulty and examining whether adding automatically generated documentation or richer metadata improves retrieval performance. I think this would help us better understand the strengths and limitations of each approach.

**4. What other techniques would you be interested in using in your project?**

I would be interested in exploring learning-to-rank methods and LLM-based reranking to improve the relevance of retrieved datasets. Another technique would be query expansion, where an LLM reformulates a user's question to improve retrieval. I would also like to experiment with combining structured metadata and vector embeddings in a hybrid search system. These techniques could help us build a retrieval pipeline that is more accurate and robust across different query types.
