# Mitigating Mathematical Context Degradation in Physics Documents through Formula-Aware Chunking in RAG Architectures

This repository contains the dataset, experiment scripts, and evaluation logs for the research paper submitted for the Mid-Exam of Research Methodology in Computer Science.

## 📌 Project Overview
Standard Retrieval-Augmented Generation (RAG) pipelines often suffer from "mathematical context degradation" when parsing STEM documents. Fixed-size chunking blindly severs mathematical formulas from their explanatory text. This project introduces a **Formula-Aware Chunking** preprocessing step designed to detect equation boundaries and preserve the semantic link between physics theories and their mathematical representations.

## 📂 Repository Structure
* `/data/raw/`: Original open-source physics PDF textbooks (e.g., OpenStax).
* `/data/processed/`: Extracted markdown text and LaTeX formulas.
* `/notebooks/`: Jupyter Notebooks containing the extraction, chunking, and RAG evaluation code.

## 🛠️ Proposed Methodology
1. **Extraction:** PDF to Markdown + LaTeX translation using Visual Transformers (Nougat).
2. **Chunking:** Comparative testing between baseline (Fixed-size 500-tokens) vs. Experimental (Formula-aware semantic logic).
3. **Evaluation:** Automated QA testing using the RAGAS framework (Faithfulness and Context Precision metrics).

## 👨‍💻 Author
* **Name:** Rafael sacchi
* **Student ID:** 2802404816
* **Institution:** School of Computer Science, BINUS University
