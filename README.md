# Enhancing Mental Health Care with Sinhala Voice-Based Chatbot

## Overview
This project aims to address the gap in accessible mental health care in Sri Lanka by developing an intelligent, voice-based chatbot that provides mental health support in **Sinhala**. The chatbot leverages **Natural Language Processing (NLP)** and **Machine Learning** to generate empathetic, contextually accurate responses, bridging cultural and linguistic barriers in mental health care.

## Features
- **Dual-Model Approach**:
  - **Bi-LSTM Model** for context-aware response generation.
  - **Retrieval-Augmented Generation (RAG)** for enhanced accuracy in low-confidence scenarios.
- **Voice Interaction**:
  - Integrated **Speech-to-Text** (Web Speech API) and **Text-to-Speech** (Google TTS).
- **Translation Pipeline**:
  - Sinhala-English-Sinhala translation for leveraging English datasets.
- **High Accuracy**:
  - Bi-LSTM model achieves **95.54%** accuracy.
- **Dynamic Retrieval**:
  - Uses **FAISS** and **LangChain** for efficient document retrieval.

## Technologies Used
- **Frontend**:
  - React with Web Speech API for voice input.
- **Backend**:
  - Flask for API handling.
  - TensorFlow for training Bi-LSTM models.
  - LangChain for RAG implementation.
- **Machine Learning**:
  - GloVe embeddings for semantic understanding.
  - LLaMA and Hugging Face Transformers for RAG-based responses.
- **Other Tools**:
  - Faiss for document retrieval.
  - gTTS for Sinhala text-to-speech conversion.

## Setup and Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/sinhala-mental-health-chatbot.git
