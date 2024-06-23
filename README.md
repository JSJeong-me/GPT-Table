# GPT-Table
### GPT Table Semantic Parsing [[Paper](https://drive.google.com/file/d/1edpW9TkiNPAEhD5NvFgQOv2i73wFiEBz/view?usp=sharing)] [[Presentation](https://drive.google.com/file/d/1SwL9L86k7TUbbC0vaRMbVe8fn9EFTrPl/view?usp=sharing)]

# An Empirical Study of the Structural Understanding Capabilities of LLMs on Financial Document Tables
# Abstract

In recent years, large language models (LLMs) have been recognized for their zero-shot reasoning capabilities in natural language processing tasks. However, their proficiency in handling structured data formats, particularly tables, has not been as extensively explored. Despite demonstrating substantial abilities in interpreting structured data, the inherent multidimensional nature of tables presents unique challenges that may impede full comprehension by LLMs. This challenge is particularly critical in the context of financial documents, where precision in numerical interpretation is crucial. Accurate data interpretation ensures reliable financial analysis and decision-making. Therefore, it is essential to address the propensity of LLMs to "hallucinate" or produce erroneous outputs when dealing with tabular data in financial contexts. Enhanced accuracy in processing such data not only supports compliance and reporting standards but also bolsters trust in automated systems for financial analysis. 
In this study, we focused on finance-related documents, converting various types of financial documents, including corporate financial disclosures, invoices, and receipts, into XML format and represented as a tuple. This conversion facilitates accurate understanding and implementation of table question answering using LLMs. We provided an analysis example using a tax invoice with a complex table structure to illustrate this method. This approach demonstrates the potential for automating the processing of various financial documents such as corporate disclosures, invoices, and receipts with high accuracy and without errors. Our code is available at
https://github.com/JSJeong-me/GPT-Table.


![fig-0](https://github.com/JSJeong-me/GPT-Table/assets/54794815/88f1bc23-3624-47f1-8744-51caa3e60b88)
### Fig. 1.  Example of reorganizing a complex form area into an Excel table

---

![fig-01](https://github.com/JSJeong-me/GPT-Table/assets/54794815/40738e0e-6ee2-48bb-8392-8024514b269f)
### Fig. 2.  An Overview of Structured Data Extraction from Complex Tables for LLM Q&A

---

![fig-3](https://github.com/JSJeong-me/GPT-Table/assets/54794815/109bd86c-9166-40b3-a33c-3e2afc0a54f3)
### Fig. 3.  Three-Tuple Values Related to 'Total Tax' Summary


