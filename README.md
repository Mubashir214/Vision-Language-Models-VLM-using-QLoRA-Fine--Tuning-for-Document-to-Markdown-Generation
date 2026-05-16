# Vision Language Models (VLM) using QLoRA Fine-Tuning for Document-to-Markdown Generation

## 📌 Project Overview

This project focuses on fine-tuning a Vision Language Model (VLM) using **QLoRA (Quantized Low-Rank Adaptation)** for converting document images into structured Markdown format.

The model learns to understand:
- Document layouts
- Text structures
- Tables
- Headings
- Mathematical content
- Multi-modal image-text relationships

The pretrained model used in this project is:

- Qwen2-VL-2B-Instruct

The fine-tuning process is performed using:
- Hugging Face Transformers
- PEFT (LoRA)
- BitsAndBytes 4-bit Quantization
- PyTorch

The project is implemented and trained on:
- Kaggle Notebook
- Dual GPU T4 ×2 Accelerator

---

# 🎯 Objectives

The main objectives of this project are:

- Understand multimodal learning (vision + language)
- Fine-tune a Vision Language Model efficiently
- Apply QLoRA for parameter-efficient training
- Generate Markdown documentation from document images
- Compare generated outputs with ground-truth markdown

---

# 🧠 Model Used

## Qwen2-VL-2B-Instruct

A powerful Vision Language Model capable of:
- Understanding images
- Processing text instructions
- Generating structured outputs

Model Link:
https://huggingface.co/Qwen/Qwen2-VL-2B-Instruct

---

# 📂 Dataset

## Nougat Training Dataset Example

Dataset Link:
https://www.kaggle.com/datasets/zphilip/nougat-training-dataset-example

The dataset contains:
- Document images
- Corresponding Markdown outputs

Examples include:
- Research papers
- Structured documents
- Scientific layouts

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| Hugging Face Transformers | Model Loading & Training |
| PEFT | LoRA Fine-Tuning |
| BitsAndBytes | 4-bit Quantization |
| Accelerate | Multi-GPU Training |
| Gradio / Streamlit | Deployment |
| Kaggle | Training Platform |

---

# 🏗️ Project Workflow

## 1. Environment Setup

### Platform
- Kaggle Notebook

### GPU
- Dual GPU T4 ×2

### Required Libraries

```bash
pip install transformers
pip install accelerate
pip install peft
pip install bitsandbytes
pip install datasets
pip install trl
pip install gradio
pip install streamlit
