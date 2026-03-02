# Homeopathic Medicine Suggestor: RAG based Assistant Agent

> A RAG framework developed during the Google 5-Day Agentic AI Course, simulates retriveing and suggesting medicines form given data for doctor.
**Data derived from the public domain 1927 9th edition of Boericke's Materia Medica and Repertory.**
---

## Table of Contents
* [Problem Statement](#problem-statement)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Setup and Usage](#setup-and-usage)
* [Demo](#demo)
* [Lessons Learned](#lessons-learned)

---

## Problem Statement
Exploring the capabilities of modern AI RAG to create specialized data retrieval system. This project aimed to build a proof-of-concept RAG, "Homeopathic Medicine Suggestor: RAG based Assistant Agent" that can retrieve data and suggest medicines from data, simulating an RAG prescription given to patient.

## Features
This Project includes usage of the following concepts:
 * Data is fed to embeddings database.
 * Create embeddings database wth ChromaDB
 * Retrieval: Find relevant documents.
 * Augmented generation: Answer the question.
 * Call LLM to generate response based on the RAG database.

## Technologies Used
*   Python 3
*   Google AI Generative Language (Gemini API)
*   Pandas for data handling
*   Kaggle Notebooks for development and experimentation
*   Generative AI agent - a chatbot
*   Prompting
*   Provides medicine suggestions based on the data feed
*   Retrieval-Augmented-Generation (RAG)
*   ChromaDB
## Setup and Usage
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AakashDeshpande-GenAI/RAG_Homeopathic-_medicine-_suggestor.git
    cd RAG_Homeopathic-_medicine-_suggestor
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Open and run the notebook:**
    *   The main logic is contained within `homeopath-rag.ipynb`. Open this in Jupyter Notebook or VS Code or Kaggle.

## Demo
**Data derived from the public domain 1927 9th edition of Boericke's Materia Medica and Repertory.**

Database:
![Database](https://raw.githubusercontent.com/AakashDeshpande-GenAI/RAG_Homeopathic-_medicine-_suggestor/refs/heads/main/Images/Database.png)
Retreieved Data:
![Retreieved Data](https://raw.githubusercontent.com/AakashDeshpande-GenAI/RAG_Homeopathic-_medicine-_suggestor/refs/heads/main/Images/Retreived_data.png)
Generated Retrieved Response:
![Generated Retrieved Response](https://raw.githubusercontent.com/AakashDeshpande-GenAI/RAG_Homeopathic-_medicine-_suggestor/refs/heads/main/Images/Generated_RAG_response.png)

## Lessons Learned
This project was a deep dive into RAG and the practical application of data and RAG by LLMs. A key challenge was ensuring the LLM responses were constrained to the provided knowledge base to prevent hallucination. This project solidified my understanding of building real-world applications with RAG.
