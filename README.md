# uk-statutory-nlp

# UK Explanatory Notes & Statutory Complexity Analysis

An NLP-based quantitative discourse project analyzing the syntactic complexity and readability gaps between UK legislative statutes and their official Explanatory Notes.

---

## Project Overview
Legal jargon and statutory provisions are notoriously complex. This project utilizes Python to programmatically measure and compare the readability profiles of **150 paired datasets** (Statutory Sections vs. Official Explanatory Notes) across **five major UK Digital Regulation Acts** (e.g., Online Safety Act, Digital Markets Act). 

The goal is to provide data-driven insights into how successfully "Explanatory Notes" translate dense legislative syntax into accessible prose.

*   **Key Achievement**: Successfully engineered a text-processing pipeline achieving **78.3% classification accuracy** in predicting document types based on linguistic features, proving significant readability gains in 108 text pairs.

---

## Tech Stack & Methodology

*   **Language**: Python 3.x
*   **Libraries**: Pandas, NumPy, Scikit-learn, NLTK, SpaCy
*   **Key NLP Techniques**: 
    *   *Readability Benchmarking*: Flesch-Kincaid Grade Level & Gunning Fog Index calculation.
    *   *Syntactic Parsing*: Dependency parsing via SpaCy to extract sentence length, subordinate clauses, and passive voice density.
    *   *Text Classification*: Feature extraction (TF-IDF + Syntactic markers) coupled with Machine Learning algorithms to classify statutory vs. explanatory texts.

---

## Key Findings & Deliverables

1.  **Readability Bridging**: 108 out of 150 pairs demonstrated a statistically significant drop in grade-level complexity, validating the cognitive utility of Explanatory Notes.
2.  **Syntactic Triggers**: Long noun-phrases and passive constructions were identified as the primary drivers of statutory complexity, which the classification model mapped with **78.3% accuracy**.

---

## Acknowledgement & Academic Context
*   This project was developed as part of the advanced language data analytics framework at the Department of English Language and Literature, **Sungkyunkwan University**. 
*   All legislative source texts and explanatory documents were compiled directly from the official UK Legislation database (legislation.gov.uk).
