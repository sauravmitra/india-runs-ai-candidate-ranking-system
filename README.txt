# AI-Powered Candidate Ranking System

## Overview

This project presents an AI-driven candidate ranking system developed for the **India.Runs Data & AI Challenge**. The system evaluates candidates beyond traditional keyword matching by considering skills, professional experience, achievements, and educational background.

The objective is to provide explainable and reliable candidate recommendations for recruitment and talent acquisition.

---

## Problem Statement

Build an intelligent candidate ranking solution that understands candidate profiles and ranks them based on multiple factors rather than relying solely on keyword matching.

---

## Features

* Multi-factor candidate evaluation
* Weighted scoring methodology
* Explainable AI recommendations
* Confidence score generation
* Skill and experience analysis
* Transparent ranking mechanism

---

## Project Structure

```text
india-runs-ai-candidate-ranking-system/

├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── ranking_model.py
│   ├── explainability.py
│   ├── candidate_data.py
│   ├── similarity_search.py
│   ├── evaluation_metrics.py
│   ├── app.py
│   └── main.py
│
├── notebooks/
│   └── candidate_ranking_analysis.ipynb
│
├── diagrams/
│   ├── system_architecture.png
│   └── workflow.png
│
├── screenshots/
│   ├── output1.png
│   └── output2.png
│
├── presentation/
│   └── India_Runs_AI_Candidate_Ranking_System_Presentation.pptx
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Ranking Methodology

The final score is calculated using weighted scoring:

```python
Final Score =
0.40 × Skill Match +
0.30 × Experience Score +
0.20 × Achievement Score +
0.10 × Education Score
```

---

## Candidate Evaluation Example

| Criteria                | Score  |
| ----------------------- | ------ |
| Relevance of Skills     | 8.0/10 |
| Professional Experience | 8.5/10 |
| Achievements            | 9.0/10 |
| Education               | 8.5/10 |

### Overall Score

**8.5 / 10**

### Recommendation

**Highly Recommended**

### Confidence Score

**85%**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook
* Flask

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Running the Project

```bash
python main.py
```

---

## Sample Output

```text
Candidate Ranking Result
------------------------
Skill Score: 8.0
Experience Score: 8.5
Achievement Score: 9.0
Education Score: 8.5
Final Score: 8.5
Recommendation: Highly Recommended
```

---

## Workflow

```text
Candidate Profile
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Weighted Scoring
        ↓
Explainability Module
        ↓
Confidence Score Generation
        ↓
Final Candidate Ranking
```

---

## Future Improvements

* Sentence Transformers
* FAISS Vector Search
* Streamlit Dashboard
* LLM-based Explainability
* Semantic Candidate Matching
* Retrieval-Augmented Generation (RAG)

---

## Author

**Saurav Mitra**

India.Runs Data & AI Challenge Submission
