# NLP Preprocessing Engine 🚀

## 📌 Overview

This project is part of the **Data Science Internship – February 2026 Assignment**.
The goal is to build a robust and scalable NLP preprocessing pipeline that converts raw, noisy text into clean and meaningful tokens suitable for machine learning models.

---

## 🎯 Objectives

* Handle real-world noisy text data
* Perform text normalization
* Build a reusable preprocessing pipeline
* Conduct token-level analysis
* Ensure clean and maintainable code

---

## 🛠️ Features Implemented

### ✔ Text Preprocessing

* Convert text to lowercase
* Remove numbers
* Remove URLs and email patterns
* Remove special characters and emojis
* Handle repeated characters
* Remove extra spaces
* Remove short tokens (≤ 2 characters)
* Preserve important words like **"no"** and **"not"**

---

### ✔ Stress Testing

Tested on diverse real-world sentences including:

* Emojis 😍
* Slang
* URLs
* Numbers
* Mixed case text

---

### ✔ Token Analytics

For each sentence:

* Total number of tokens
* Unique tokens
* Average token length

---

### ✔ Frequency Analysis

* Top 10 most frequent words
* Top 5 least frequent words

---

### ✔ Full Pipeline

Implemented a complete pipeline function:

```python
def full_pipeline(text_list):
    return {
        "tokens": [...],
        "clean_sentences": [...]
    }
```

---

### ✔ Error Handling

Handled edge cases:

* Empty string
* Only emojis
* Only numbers

---

## 📌 Key Learnings

* Importance of text cleaning in NLP
* Handling noisy real-world data
* Designing modular pipelines
* Performing token-level analysis

---


## ⭐ Conclusion

The developed NLP preprocessing engine effectively transforms raw text into structured data. This pipeline can be directly used as a preprocessing step for NLP and machine learning models.

---
