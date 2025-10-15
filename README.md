# 📄 Pahenji Akhbar – Preprocessed Sindhi News Dataset (1923 txt files)

### 📰 Source: Pahenji Akhbar (Online Sindhi Newspaper)  
Website: [epaper.pahenjiakhbar.com](https://epaper.pahenjiakhbar.com/) :contentReference[oaicite:0]{index=0}  
### 📤 Prepared & Uploaded by: *Abdul Majid Bhurgiri, Institute of Language Engineering*  
### 📅 Release Year: 2025  
### 🌍 Language: Sindhi (سنڌي)  
### 📦 Dataset Type: Preprocessed News & Articles Corpus

---

## 📖 Overview

This repository contains a cleaned and preprocessed corpus of **Pahenji Akhbar** news articles and content in Sindhi. The raw data has been processed to remove noise and normalize text, making it suitable for **NLP model training**, research, and language engineering applications.

The dataset aims to support tasks such as language modeling, classification, summarization, and more in the Sindhi language domain.

---

## 🧹 Preprocessing & Cleaning

To ensure high data quality, the following cleaning steps were applied:

- Removal of **email addresses**, **URLs** and **links**  
- Elimination of **special characters**, symbols, and **emojis**  
- Filtering out segments in **other languages** (non-Sindhi text)  
- Normalization of Sindhi **Unicode characters**  
- Removal of unnecessary whitespace, repeated punctuation, and formatting artifacts  
- Ensuring **UTF-8 encoding** for all text content  

The final output is a clean, consistent Sindhi-language news corpus ready for downstream NLP tasks.

---

## 📁 Dataset Structure & Files

| File Name | Description | Format | Encoding |
|-----------|-------------|--------|-----------|
| `PahenjiAkhbar_Preprocessed.txt` | Cleaned Sindhi news corpus from Pahenji Akhbar articles | `.txt` | UTF-8 |

Each line (or paragraph) in the text file corresponds to a cleaned news segment from the original source.

You may add supplemental metadata files later (e.g., article dates, sources, titles) if available.

---

## 🧠 Research & Application Use Cases

This dataset can be used for:

- 🗣️ **Language Modeling / Sindhi LLMs**  
- 💬 **News Summarization & Headline Generation**  
- 📊 **Sentiment / Tone Classification**  
- 🌐 **Machine Translation** (Sindhi ↔ English, Sindhi ↔ Urdu)  
- 🌍 **Named Entity Recognition**, **Topic Modeling**, **Information Extraction**  
- 🧩 **Embedding Training** for Sindhi text  

---

## ⚙️ Example Usage (Python)

```python
with open("PahenjiAkhbar_Preprocessed.txt", "r", encoding="utf-8") as f:
    corpus = f.readlines()

# Example: print first 3 segments
for i in range(3):
    print(corpus[i])
