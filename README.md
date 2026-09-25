# GitHub Issues Dataset

Dataset of GitHub Issues used for research and development of a
Retrieval-Augmented Generation (RAG) system for factual solution generation.

---

## 📌 Description

This repository provides the GitHub Issues dataset used in an undergraduate
research project focused on Retrieval-Augmented Generation (RAG).

The dataset contains GitHub Issues and related information prepared for
text processing, semantic retrieval, and evaluation.

---

## 📦 Dataset

The dataset is provided through the GitHub Releases section.

### Dataset file

- `github_issues_tickets.csv`
- Size: approximately 40 MB
- Format: CSV

The dataset can be downloaded from:

[Download Dataset](../../releases/tag/1.0)

---

## 🔬 Research Context

The dataset was used in the development of a RAG system for generating
factual solutions from GitHub Issues.

The research pipeline includes:

- Text preprocessing
- Sentence-BERT for semantic retrieval
- FAISS for vector search
- CrossEncoder for reranking
- FLAN-T5 for response generation

The dataset was used for model development, retrieval corpus construction,
and system evaluation.

---

## 💻 Usage

The dataset can be downloaded from the Release section and loaded into
Python or Google Colab for further processing and experimentation.

Example:

```python
import pandas as pd

df = pd.read_csv("github_issues_tickets.csv")

print(df.head())
print(df.shape)
