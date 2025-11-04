# BERT-based Question Answering Demo

This repository contains a **Jupyter Notebook** (`BERT.ipynb`) demonstrating how to build a simple **Question Answering (QA)** system using the **BERT model** from Hugging Face’s Transformers library.  
It showcases the core concepts of **Natural Language Processing (NLP)** and **extractive QA**, where the model identifies the span of text in a passage that best answers a given question.

---

## Overview
This project serves as a hands-on demo to understand how **transformer-based language models** like **BERT** process and extract contextual meaning from text.  
It includes:
- Loading and using a **pretrained BERT model** for question answering  
- Tokenization and encoding using Hugging Face’s tokenizer  
- Performing inference to extract the most relevant answer span  
- Visualizing the question, context, and predicted answer  

---

## Model Workflow
1. **Input**: A paragraph of text (context) and a question.  
2. **Tokenization**: The text and question are encoded into tokens using BERT’s tokenizer.  
3. **Inference**: The tokens are passed into the pretrained BERT model.  
4. **Output**: The model predicts the start and end positions of the answer within the context.  
5. **Result**: The extracted answer is displayed as plain text.

---

## Tech Stack
- **Python 3.10+**  
- **PyTorch**  
- **Transformers (Hugging Face)**  
- **Jupyter Notebook**

---

## Installation
To run this notebook locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/bert-qa-demo.git
cd bert-qa-demo

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate   # for macOS/Linux
venv\Scripts\activate      # for Windows

# Install dependencies
pip install torch transformers notebook
