# 📝 Extractive Text Summarization using TF-IDF and PageRank

This project performs **Extractive Text Summarization** using Natural Language Processing (NLP) techniques. It uses **TF-IDF vectorization**, a **similarity matrix**, and **PageRank algorithm** to select the most informative sentences from a given document. The final summary is evaluated using **ROUGE scores**.

---

## 📌 Features

- Sentence tokenization using `nltk`
- Stopword removal
- TF-IDF vectorization with unigrams and bigrams
- Cosine similarity matrix for sentence comparison
- Graph-based ranking using `networkx.pagerank()`
- Extracts top-ranked sentences as summary
- Summary evaluation using ROUGE-1, ROUGE-2, and ROUGE-L

---

## 📁 File Structure

```bash
.
├── ML_Project.ipynb          # Colab implementation
├── README.md                    # Project overview and documentation


## 🔐 Disclaimer

- This project implements a **basic extractive text summarization** approach.  
- It selects the most relevant sentences from the input text based on **TF-IDF** and **PageRank**, without generating new phrases or paraphrasing like in **abstractive summarization**.
- It is intended for **educational and learning purposes only**, and not optimized for large-scale or production-level use.
- Evaluation is done using **ROUGE metrics**, which measure similarity to the original document but do not always reflect human judgment of quality.
- Performance may vary depending on the length and style of the input text.
