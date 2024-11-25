# Realtime document Chat System using LLM

## Table of Content

- [Project Summary](#project-summary)
- [Project Live Link](#project-live-link)
- [Technologies Used](#technologies-used)
- [Implementation Steps](#implementation-steps)

## Project Summary

This project is a Conversational Retrieval-Augmented Generation (RAG) system that enables users to upload PDF documents, extract meaningful content, and interact conversationally with the uploaded material. The system is powered by cutting-edge technologies for efficient document indexing and natural language processing.

- **Document Processing:** Allows users to upload PDFs, which are then processed and split into manageable text chunks for indexing.
- **Vector Database:** Leveraged Chroma Vector Database for efficient storage and retrieval of document embeddings, ensuring fast and accurate contextual searches.
- **Large Language Model:** Integrated Groq's Gemma2-9b-It LLM, a robust 9-billion-parameter model, for generating human-like responses and reformulating context-aware questions.
- **Chat History Management:** Retains conversational context to provide more precise and relevant answers by utilizing LangChain's ChatMessageHistory.
- **Interactive Frontend:** Built using Streamlit, offering a user-friendly interface for uploading files, asking questions, and reviewing responses.

---

## Project Live Link

Check out the live project!

[Document Chat App](https://rag-q-a-with-pdf-fnappldaix8hqxrd6niqqia.streamlit.app/)

---

## Technologies Used

- **Python**
- **Streamlit**
- **Chroma Vector DB**
- **HuggingFace Embeddings**
- **Groq (Gemma2-9b-It LLM Model)**
- **LangChain**

---

## Implementation Steps

- Create a Groq API key from Groq Cloud platform.[GroqCloud](https://console.groq.com/login)
- Copy and Paste the API key in the Input field.
- Upload any document and ask questions!


