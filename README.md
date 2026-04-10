# Section-Aware-Legal-Retrieval
Advanced analysis and retrieval of structured Turkish court decisions. Methodological study accepted for Springer CCIS.

# Turkish Legal Document Analysis & Retrieval

## Overview
This project focuses on the digitalization, structuring, and advanced analysis of scanned Turkish legal documents (PDFs). The primary goal is to optimize legal research by leveraging Large Language Models (LLMs) and hybrid retrieval architectures.

## Technical Highlights
* **Document Structuring**: Utilizing Vision-Language Models (VLM) to segment scanned judicial decisions into role-labeled sections such as Facts, Reasoning, and Verdict.
* **Hybrid Retrieval Architecture**: Combining lexical ($BM25$) and semantic (dense bi-encoder) search methods tailored for Turkish legal terminology.
* **Section-Aware Analysis**: Investigating the retrieval signals of different document segments to improve the accuracy of finding relevant precedents.

## Tech Stack
* **Language**: Python
* **Models**: Transformer-based Encoders (e.g., $MPNet$, $XLM-R$) and Multimodal VLMs.
* **Core Methods**: RAG (Retrieval-Augmented Generation), $BM25$, and Sparse-Dense Hybrid Fusion.

## Academic Recognition
The methodology developed in this project has been peer-reviewed and accepted for publication in the **Springer CCIS** series as part of the **ITTA 2026** international conference.

> **Note**: Due to the ongoing academic publication process and data privacy considerations, the full source code and datasets are currently restricted. Methodological details will be made accessible following official publication.
