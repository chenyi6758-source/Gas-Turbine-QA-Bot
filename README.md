# Gas Turbine Maintenance QA Bot

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)

## 📌 Project Overview
This project is an AI-powered Question-Answering (QA) Bot designed to assist engineers by instantly retrieving relevant solutions from equipment maintenance manuals. It demonstrates the fundamental logic of **Retrieval-Augmented Generation (RAG)** using Natural Language Processing (NLP).

## 🛠️ Tech Stack
- **Language:** Python 3.8+ with Scikit-Learn and Pandas for NLP processing
- **Libraries:** Scikit-Learn (TF-IDF Vectorizer, Cosine Similarity), Pandas
- **Domain:** Natural Language Processing (NLP), Semantic Search

## 🧠 Core Features
- **Text Vectorization:** Converts human queries and equipment manual rules into mathematical vectors using TF-IDF algorithms.
- **Semantic Search:** Uses Cosine Similarity to find the most relevant maintenance protocol based on the engineer's natural language input.
- **Thresholding:** Implemented confidence scoring to filter out irrelevant queries and prevent AI hallucinations.

## 📂 Project Structure
- `Turbine_QA_Bot.ipynb`: The main notebook containing the NLP search engine and interactive bot.

## 🔧 Installation

Requires Python 3.8+. Install the required Jupyter and NLP packages:

    pip install jupyter pandas numpy scikit-learn

## 🚀 Usage

Start the Jupyter Notebook server by running the `jupyter notebook` command, then open `Turbine_QA_Bot.ipynb` in your browser and run the cells step by step to interact with the QA bot.
