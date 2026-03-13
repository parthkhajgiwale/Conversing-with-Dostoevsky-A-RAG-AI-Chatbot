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
Install dependencies:

```bash
pip install -r requirements.txt
```

# Running the Project

Open the notebook: Conversing_with_Dostoevsky_A_Retrieval_Augmented_Generative_AI_Chatbot.ipynb


Run all cells to:

- Load Dostoevsky texts  
- Build embeddings  
- Store vectors in **ChromaDB**  
- Start the chatbot  

---

# Example Questions

Try asking the chatbot:

- Why do humans suffer?  
- Is conscience stronger than punishment?  
- Can guilt lead to redemption?  
- Are humans naturally good or evil?  
- Is freedom a blessing or a burden?  

---

# Example Output

> "My dear reader, suffering is perhaps the most terrible privilege granted to man.  
> The animal suffers and forgets, yet man remembers, questions, rebels against the injustice of existence itself..."

---

# Project Goal

The goal of this project is to demonstrate how **Retrieval-Augmented Generation (RAG)** can be used to simulate literary voices and philosophical dialogue by combining modern AI techniques with classic literature.

---

# Future Improvements

- Improve literary style conditioning  
- Add support for multiple philosophers  
- Evaluate responses using semantic similarity  
- Build a web interface for interaction  

