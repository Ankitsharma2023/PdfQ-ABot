﻿# 📚 Research Paper Analyser

## 🧠 Problem Statement

Research papers are lengthy, dense, and often difficult to understand quickly. Yet, they form the **core foundation of knowledge** in academia and innovation.

**But the problem is:**
- Reading them takes significant time.
- Important insights are often buried deep.
- Not everyone is skilled in understanding academic jargon.

This project solves this by turning any uploaded research paper into an **interactive chatbot** — ask any question and get answers based on the paper, instantly.

## ✨ Features

- **PDF Upload and Processing**: Direct upload and intelligent parsing of research papers
- **Interactive Q&A**: Ask questions about the paper and get specific answers
- **Academic Focus**: Designed specifically for research paper analysis
- **Conversation History**: Track all your previous interactions and questions for easy reference
- **Concise Summaries**: Get clear, to-the-point answers without unnecessary complexity
- **Free & Open Source**: Completely free to use with open-source code available to all
- **Section-Specific Queries**: Ask about particular sections or figures in the paper

## 🚀 How Is This Better Than ChatGPT?

| Feature | ChatGPT | Research Paper Analyser |
|--------|---------|--------------------------|
| Answers based on your document only | ❌ May hallucinate / use general data | ✅ 100% based on your paper |
| Maintains chat context | Limited | ✅ Session-based history |
| Built for researchers | ❌ General-purpose | ✅ Focused on academic papers |
| Custom PDF chunking and retrieval | ❌ No control | ✅ Tuned with LangChain & embeddings |
| Offline paper analysis | ❌ Needs copy-paste | ✅ Direct PDF upload and processing |

## ⚙️ Setup Instructions

Follow these steps to run the app locally:

### 1. 🧬 Clone the Repository
```bash
git clone https://github.com/Ankitsharma2023/ResearchPaperAnalyser
```

### 2. 📂 Navigate into the Project Directory 
```bash
cd ResearchPaperAnalyser
```

### 3. 📥 Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. 🚀 Run the Application
```bash
streamlit run app.py
```
