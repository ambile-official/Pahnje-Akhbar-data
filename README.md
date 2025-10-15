# 📰 Pahenji Akhbar – Preprocessed Sindhi News Dataset 

### 🏛️ Source: [Pahenji Akhbar (Sindhi Newspaper)](https://epaper.pahenjiakhbar.com/)  
### 📤 Prepared & Uploaded by: *Abdul Majid Bhurgiri, Institute of Language Engineering*  
### 🌐 Official Uploading Credit: [ambile.pk](https://ambile.pk/)  
### 📅 Release Year: 2025  
### 🌍 Language: Sindhi (سنڌي)  
### 📦 Dataset Type: Preprocessed News & Articles Corpus  (1923 txt files)

---

## 📖 Overview

The **Pahenji Akhbar Dataset** is a comprehensive and preprocessed collection of **Sindhi news articles and editorial content** extracted from the *Pahenji Akhbar* publication.  

This dataset has been cleaned, standardized, and structured for **Natural Language Processing (NLP)** and **AI language research**.  
It provides high-quality Sindhi text ideal for tasks such as **language modeling**, **summarization**, **classification**, and **machine translation**.

---

## 🧹 Data Cleaning & Preprocessing

The dataset was carefully preprocessed to ensure quality and model-readiness.  
All irrelevant or noisy data were removed, including:

- ✅ Email addresses  
- ✅ URLs and external links  
- ✅ Special characters and punctuation noise  
- ✅ Emojis and symbols  
- ✅ Non-Sindhi or foreign language content  
- ✅ Extra line breaks and unnecessary spaces  
- ✅ Normalized Sindhi Unicode text  
- ✅ Standardized to **UTF-8** encoding  

This makes the dataset clean, consistent, and ready for direct use in Sindhi NLP pipelines.

---

## 📂 Dataset Contents

| File Name | Description | Format | Encoding |
|------------|-------------|---------|-----------|
| `PahenjiAkhbar_Preprocessed.txt` | Cleaned Sindhi news and article corpus from Pahenji Akhbar | `.txt` | UTF-8 |

Each line or paragraph represents a preprocessed Sindhi article segment.

---

## 🧠 Research & Application Use Cases

This dataset supports a wide range of **Sindhi AI and NLP applications**, including:

- 🗣️ **Language Modeling** — Train Sindhi GPT or transformer-based models  
- 💬 **Conversational Systems** — Build Sindhi chatbots and dialogue engines  
- 📊 **Sentiment Analysis** — Detect tone, emotion, and opinion in news content  
- 📰 **Summarization Models** — Generate Sindhi news summaries automatically  
- 🌐 **Machine Translation** — Develop Sindhi ↔ English or Sindhi ↔ Urdu systems  
- 🧩 **Embedding & Tokenization Research** — Enhance multilingual embedding models  

---

## ⚙️ Technical Details

- **Data Source:** Pahenji Akhbar (Official Sindhi Newspaper)  
- **Text Domain:** News, opinions, culture, and editorial articles  
- **File Format:** Plain text (`.txt`)  
- **Encoding:** UTF-8  
- **Data Size:** Depends on total collected articles (expandable corpus)  
- **Preprocessing Quality:** Manually verified and standardized  

### Example (Python)
```python
with open("PahenjiAkhbar_Preprocessed.txt", "r", encoding="utf-8") as f:
    text = f.read()

print(text[:500])  # Preview the first 500 characters
