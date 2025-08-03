# 📰 News Article Summarizer

A lightweight NLP-based summarization tool that condenses long news articles into clear, concise summaries using state-of-the-art language models from Hugging Face.

This project demonstrates both **abstractive** and **extractive** summarization techniques using pre-trained transformer models, making it ideal for automation tools, content compression, and real-time information filtering.

---

## ✨ Key Features

- **Abstractive Summarization**  
  Uses models like `facebook/bart-large-cnn` to generate human-like, paraphrased summaries.

- **Minimal & Modular**  
  Single-notebook implementation, easy to extend or deploy as an API or script.

- **Real Article Handling**  
  Accepts long-form text input from actual news articles (supports scraped or pasted content).

- **No Fine-Tuning Required**  
  Built entirely with zero-shot models — no retraining necessary.

---

## 🔍 Technologies Used

- Python 3
- Hugging Face Transformers (`BartForConditionalGeneration`, `T5ForConditionalGeneration`)
- Tokenizers & Pipelines for LLM inference
- Jupyter Notebook

---

## 📌 Sample Output

**Original Article Excerpt:**  
> "The government today announced sweeping reforms in the energy sector..."

**Generated Summary:**  
> "Government announces major energy sector reforms."

---

## 💼 Ideal Use Cases

- News & media summarization
- RSS feed processing
- Email digest generation
- Voice assistant response building
- LLM agent pipeline module

---

## 📁 Repo Purpose

This project highlights applied NLP skills using modern LLM tools. It is well-suited for integration into production environments or as a technical portfolio showcase for NLP capabilities.

---

