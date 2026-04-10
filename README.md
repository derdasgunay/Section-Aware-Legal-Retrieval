# Section-Aware-Legal-Retrieval
Advanced analysis and retrieval of structured Turkish court decisions. Methodological study accepted for Springer CCIS.

# Turkish Legal Document Analysis & Retrieval

## Overview
[cite_start]This project focuses on the digitalization, structuring, and advanced analysis of scanned Turkish legal documents (PDFs)[cite: 6, 7]. [cite_start]The primary goal is to optimize legal research by leveraging Large Language Models (LLMs) and hybrid retrieval architectures[cite: 14, 59, 60].

## Technical Highlights
* [cite_start]**Document Structuring**: Utilizing Vision-Language Models (VLM) to segment scanned judicial decisions into role-labeled sections such as Facts, Reasoning, and Verdict[cite: 8, 34, 86].
* [cite_start]**Hybrid Retrieval Architecture**: Combining lexical ($BM25$) and semantic (dense bi-encoder) search methods tailored for Turkish legal terminology[cite: 9, 159, 161, 163].
* [cite_start]**Section-Aware Analysis**: Investigating the retrieval signals of different document segments to improve the accuracy of finding relevant precedents[cite: 7, 30, 213].

## Tech Stack
* **Language**: Python.
* [cite_start]**Models**: Transformer-based Encoders (e.g., $MPNet$, $XLM-R$) and Multimodal VLMs[cite: 85, 164, 165].
* [cite_start]**Core Methods**: RAG (Retrieval-Augmented Generation), $BM25$, and Sparse-Dense Hybrid Fusion[cite: 52, 161, 167, 270].

## Academic Recognition
[cite_start]The methodology developed in this project has been peer-reviewed and accepted for publication in the **Springer CCIS** series as part of the **ITTA 2026** international conference[cite: 1, 14].

> **Note**: Due to the ongoing academic publication process and data privacy considerations, the full source code and datasets are currently restricted. Methodological details will be made accessible following official publication.
