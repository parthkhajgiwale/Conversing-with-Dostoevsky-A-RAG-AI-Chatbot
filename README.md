# Conversing with Dostoevsky
### A Retrieval-Augmented Generative AI Chatbot

This project builds a **Generative AI chatbot that responds in the philosophical voice of Fyodor Dostoevsky**.

The system uses **Retrieval-Augmented Generation (RAG)** to retrieve passages from Dostoevsky’s works and guide a language model to generate reflective responses inspired by his literary style.

---

# Overview

Fyodor Dostoevsky explored deep themes such as:

- human suffering
- guilt and conscience
- morality and redemption
- freedom and faith
- the complexity of the human soul

This chatbot allows users to ask philosophical questions and receive answers **written in a style resembling Dostoevsky's narrative voice**.

---

# Architecture

The project follows a **Retrieval-Augmented Generation (RAG) pipeline**:
User Question
↓
Retriever (ChromaDB)
↓
Relevant Dostoevsky passages
↓
Prompt conditioning
↓
Language Model
↓
Philosophical response


### Pipeline Steps

1. **Document Loading**
   - Dostoevsky novels are loaded from PDF files.

2. **Text Chunking**
   - Documents are split into smaller text segments.

3. **Embedding Generation**
   - Sentence embeddings are created for each chunk.

4. **Vector Database**
   - Embeddings are stored in **ChromaDB**.

5. **Retrieval**
   - Relevant passages are retrieved for each user question.

6. **Prompt Engineering**
   - The model is instructed to respond in Dostoevsky's voice.

7. **LLM Generation**
   - The model produces a philosophical reflection.

---

# Technologies Used

- **Python**
- **LangChain**
- **ChromaDB**
- **Sentence Transformers**
- **HuggingFace Transformers**
- **Jupyter Notebook**

---

# Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/dostoevsky-chatbot.git
cd dostoevsky-chatbot
```
pip install -r requirements.txt
