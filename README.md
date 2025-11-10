# 🧠 Wikipedia Q&A Bot

An intelligent Question Answering system that retrieves information from **Wikipedia** and provides concise answers to user queries using **Natural Language Processing (NLP)** and **Transformer Models**.

---

## 🚀 Project Overview

This project builds a chatbot capable of answering questions in real-time using Wikipedia as its knowledge base.  
It combines information retrieval and transformer-based question answering to deliver accurate responses.

---

## 🎯 Objective

To design a chatbot that can:
- Understand natural language questions.
- Retrieve relevant content from Wikipedia.
- Generate precise answers using NLP models.

---

## ⚙️ Workflow

1. **Input Query:**  
   The user asks a question in natural language.

2. **Wikipedia Search:**  
   Relevant articles are fetched using the `wikipedia` Python library or preprocessed datasets like `wiki_dpr`.

3. **Context Extraction:**  
   The most relevant paragraph or section is extracted.

4. **Answer Generation:**  
   A pretrained QA model (e.g., DistilBERT, T5, or BERT QA) identifies the correct answer span.

5. **Output:**  
   The final summarized answer is displayed with the corresponding Wikipedia source link.

---

## 🧩 Features

✅ Real-time Wikipedia search  
✅ Transformer-based question answering  
✅ Summarized, human-readable responses  
✅ Extendable into a RAG (Retrieval-Augmented Generation) pipeline  
✅ Optional web interface using Gradio or Streamlit  

---

## 📚 Dataset

Uses the **Wikipedia** dataset — either fetched live using APIs or loaded via preprocessed corpora such as `wiki_dpr` on Hugging Face Datasets.

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:**
  - `wikipedia`
  - `transformers`
  - `datasets`
  - `torch`
  - `faiss`

