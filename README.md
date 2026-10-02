# AI Attention Visualizer · Streamlit

🔗 **Live Demo:** [AI Attention Visualizer](https://ai-attention-visualizer-knnpvqf3bv6mtz3bbjlqst.streamlit.app/)

## Overview

AI Attention Visualizer is an interactive Streamlit application that extracts text from an uploaded image and visualizes attention scores for the extracted words.

The project demonstrates the combination of Optical Character Recognition (OCR), sentence embeddings, and the scaled dot-product attention mechanism in a simple and interactive interface.

## Features

- Upload an image
- Extract text from the image using OCR
- Process extracted text into words
- Generate word embeddings
- Calculate attention scores
- Normalize attention values
- Visualize word-level attention scores
- Display attention summary

## Technologies Used

- Python
- Streamlit
- NumPy
- Pillow
- Pytesseract
- Tesseract OCR
- Sentence Transformers

## How It Works

1. Upload an image through the Streamlit application.
2. Tesseract OCR extracts text from the image.
3. The extracted text is processed into individual words.
4. Sentence Transformer generates embeddings for the words.
5. Query, Key, and Value matrices are generated.
6. Scaled dot-product attention is calculated.
7. Attention scores are normalized.
8. The attention results are displayed in the application.

## Attention Mechanism

The project demonstrates the scaled dot-product attention concept:

```text

Attention(Q, K, V) = softmax(QKᵀ / √dₖ)V

AI-ATTENTION-VISUALIZER/
│
├── app.py
├── ocr.py
├── embedding.py
├── attention.py
├── requirements.txt
├── packages.txt
└── README.md
