# KTI_demo_student-feedback-nlp-pipeline
analyazing negative feedback using count vectorizer and sentence transformers
# Unsupervised Student Feedback NLP Analytics Pipeline

An end-to-end, unbiased Natural Language Processing (NLP) pipeline built to extract pure, action-oriented operational insights from unstructured student feedback datasets. 

This project completely bypasses manual keyword rules, pre-configured categories, and large language model (LLM) hallucinations. Instead, it uses **unsupervised spatial geometry** (`SentenceTransformers` + `K-Means`) to let the data organize itself, extracting the true, unbiased consensus voice of the student body.

---

## 🚀 Key Features

* **Zero-Bias Theme Discovery:** Replaces hardcoded keyword structures (like looking strictly for the word "navigate") with semantic vectors. It maps sentences into a 384-dimensional space based purely on underlying meaning.
* **Centroid-Based Core Extraction:** Finds the mathematical "center of gravity" for each feedback cluster and uses Euclidean distance (`distances.argmin()`) to isolate the actual student comment that represents the consensus issue.
* **Dual-Approach Architecture:**
  * **Approach 1 (Literal count):** Uses `CountVectorizer` to generate a pure frequency leaderboard of 1-to-3-word phrases (N-grams) to spot highly repeated keywords.
  * **Approach 2 (Pure Semantic):** Groups conceptually identical sentences (e.g., matching *"The assessment is too hard"* and *"The final quiz was brutal"* into the same category bucket) using coordinate clustering.
* **Unbiased Management Directives:** Automatically generates structured operational briefs, directing the Training Manager to audit specific clusters without altering or making assumptions about the data.

---
