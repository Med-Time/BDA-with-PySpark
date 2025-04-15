## 📘 BDA with PySpark – Scalable Big Data NLP Pipeline

### 📌 Overview
This project implements a scalable text mining and visualization pipeline using **Apache PySpark**. It processes the **20 Newsgroups dataset**, a classic benchmark corpus for topic classification and clustering. The primary focus is on distributed data handling, feature extraction, and exploratory visualization using scalable techniques.

### 🔍 Objective
To build a Big Data–capable Natural Language Processing (NLP) pipeline that can:
- Efficiently ingest and transform large-scale textual datasets.
- Perform basic exploratory analysis using distributed computing.
- Visualize insights through word clouds, frequency plots, and distribution graphs.

### 🧠 Key Features
- **Distributed Ingestion & Processing**  
  Utilized PySpark's DataFrame API for transforming unstructured text at scale.

- **Dataset**  
  Integrated the `20 Newsgroups` dataset using scikit-learn, pre-processed for tokenization and frequency analysis.

- **Visual Analysis**  
  Generated:
  - Word clouds for most common terms across categories.
  - Bar plots for category distribution.
  - Histograms for document length analysis.

- **Category-Level Exploration**  
  Analysis included top-k terms per category and inter-category comparisons.

- **Scalability**  
  Designed to support horizontal scaling for much larger corpora with minimal configuration changes.

