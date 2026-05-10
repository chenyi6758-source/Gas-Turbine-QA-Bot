# Gas Turbine Maintenance QA Bot

## 📌 Project Overview
This project is an AI-powered Question-Answering (QA) Bot designed to assist engineers by instantly retrieving relevant solutions from equipment maintenance manuals. It demonstrates the fundamental logic of **Retrieval-Augmented Generation (RAG)** using Natural Language Processing (NLP).

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Scikit-Learn (TF-IDF Vectorizer, Cosine Similarity), Pandas
- **Domain:** Natural Language Processing (NLP), Semantic Search

## 🧠 Core Features
- **Text Vectorization:** Converts human queries and equipment manual rules into mathematical vectors using TF-IDF algorithms.
- **Semantic Search:** Uses Cosine Similarity to find the most relevant maintenance protocol based on the engineer's natural language input.
- **Thresholding:** Implemented confidence scoring to filter out irrelevant queries and prevent AI hallucinations.

## 📂 Project Structure
- `Turbine_QA_Bot.ipynb`: The main notebook containing the NLP search engine and interactive bot.
