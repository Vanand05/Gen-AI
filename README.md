# Gen-AI: Multimodal E-commerce Chatbot Final Project

This project aims to build a **multimodal conversational AI chatbot** for e-commerce platforms that can answer customer queries using both **text and images**.

## Project Overview
Customers often upload product images or ask complex questions. This chatbot uses **Vision-Language Models**, **Retrieval-Augmented Generation (RAG)**, and a user-friendly **Streamlit interface** to provide accurate, visual-aware responses.

## Key Features
- Understands both **text** and **product images**
- Retrieves relevant product info from a large dataset (Amazon Product Dataset 2020)
- Generates responses using an open-source **LLM**
- Built-in UI for testing via **Streamlit**

## Project Structure (To be built)
multimodal-ecommerce-chatbot/
│
├── data/         ← Amazon product dataset
├── src/          ← Preprocessing, embedding, and RAG code
├── models/       ← Saved models & configs
├── notebooks/    ← Development notebooks
├── ui/           ← Streamlit-based chatbot interface
├── README.md     ← Project overview
└── requirements.txt
## Tech Stack
- Python, Streamlit
- OpenAI CLIP, Vision-Language models
- Retrieval-Augmented Generation (RAG)
- Google Vertex AI Vector Search (optional)

## Dataset
- The data is sourced from here: [Amazon Product Dataset 2020](https://www.kaggle.com/datasets/promptcloud/amazon-product-dataset-2020)

---

*This README will be updated as the project evolves.*
