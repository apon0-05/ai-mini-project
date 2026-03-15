# Multimodal AI Demo (NLP + Computer Vision)

This project demonstrates a small multimodal AI application built with Hugging Face Transformers and Streamlit.

The system combines several pretrained models to perform different AI tasks on text and images.

## Features

The application performs the following tasks:

- Question Answering using RoBERTa (deepset/roberta-base-squad2)
- Text Summarization using BART (facebook/bart-large-cnn)
- Sentiment Analysis using DistilBERT
- Zero-shot Text Classification using BART-MNLI
- Image Captioning using ViT-GPT2

## Architecture

The project integrates multiple pretrained models using the Hugging Face `pipeline` API and provides an interactive interface using Streamlit.

Workflow:

1. User inputs text or uploads an image
2. Text is processed using summarization and classification models
3. Images are processed using an image captioning model
4. Results are displayed in the Streamlit interface

## Technologies

- Python
- Hugging Face Transformers
- Streamlit
- PyTorch
- Pillow

## Running the project

Install dependencies:

```bash
pip install -r requirements.txt
