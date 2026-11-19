# Sidaamu Afoo AI Chatbot

A lightweight Retrieval-Augmented Generation (RAG) chatbot designed to assist with **Sidaamu Afoo** phrases, translations, and common questions. Built with Python, FastAPI, and Streamlit to reduce LLM hallucinations on low-resource Ethiopian languages by grounding responses in a verified dataset.

## Features
- **Grounded Responses:** Retrieves verified Sidaamu Afoo phrases from a local knowledge base before generating answers.
- **REST API:** Clean FastAPI backend with a `/chat` endpoint.
- **Interactive UI:** Minimal Streamlit web interface for quick testing.

## Tech Stack
- **Backend:** Python, FastAPI, Uvicorn
- **AI / RAG:** Gemini API (or OpenAI API), Vector/Keyword Retrieval
- **Frontend:** Streamlit

## Project Structure
- `app/main.py` — FastAPI server and API routes
- `app/rag.py` — Retrieval logic and LLM integration
- `app/ui.py` — Streamlit chat interface
- `data/phrases.json` — Verified Sidaamu Afoo dataset

## Quick Start

### 1. Clone the repository
```bash
git clone [https://github.com/Melkamukebede/sidaamu-afoo-chatbot.git](https://github.com/Melkamukebede/sidaamu-afoo-chatbot.git)
cd sidaamu-afoo-chatbot
