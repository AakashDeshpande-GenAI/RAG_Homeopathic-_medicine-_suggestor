# Homeopathic Medicine Suggestor: RAG based Assistant Agent

> A RAG framework developed during the Google 5-Day Agentic AI Course, simulates retriveing and suggesting medicines form given data for doctor.

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
 * 1. Parallel Agents - reaserching and formulating prescription
 * 2. Loop Agents - Refining prescription
 * 3. Sequential Agents - execute the aggregated prescription
 * 4. Building the Workflow - How the Agents pause - take Doctor's input - resume.
 * 5. Agent powered by an LLM - Prescriber Agents powered by gemini-2.5-flash-lite.
 * 6. Built-in tools, such as Google Search - Google search for citations
 * 7. Observability: Logging, Tracing, Metrics - Tracing Logs.
 * 8. Long Running Operations (Human In The Loop) - Taking Doctor's approval to prescription.
 * 9. Custom tool for confirmation - confirm_prescription for resuming after Doctor's approva

## Technologies Used
*   Python 3
*   Google AI Generative Language (Gemini API)
*   Pandas for data handling
*   Kaggle Notebooks for development and experimentation
*   Generative AI agent - a chatbot
*   Prompting
*   Provides medicine suggestions based on the data feed
*   Retrieval-Augmented-Generation (RAG)
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

## Lessons Learned
This project was a deep dive into RAG and the practical application of data and RAG by LLMs. A key challenge was ensuring the LLM responses were constrained to the provided knowledge base to prevent hallucination. This project solidified my understanding of building real-world applications with RAG.
