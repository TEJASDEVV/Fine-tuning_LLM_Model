# Fine-Tuning LLM using LoRA (PEFT)

This project demonstrates how to fine-tune a Large Language Model (TinyLlama)
using LoRA on limited compute (Google Colab).

# What This Project Does

This project demonstrates how to fine-tune a Large Language Model (LLM) using LoRA (Low-Rank Adaptation) on limited computing resources. Instead of training the entire model from scratch, only a small number of additional parameters are trained. This makes the fine-tuning process lightweight, faster, and feasible on platforms like Google Colab.

# Why LoRA Is Used

Training large language models normally requires powerful GPUs and a lot of memory. To solve this problem, this project uses LoRA, a parameter-efficient fine-tuning technique. LoRA freezes the original model weights and learns only small adapter layers. This significantly reduces memory usage while still allowing the model to learn domain-specific knowledge.

## Features
- Parameter-Efficient Fine-Tuning (LoRA)
- No GPU required
- Gradio-based Q&A interface
- Cybersecurity domain examples

## Use Cases
- Domain-specific question answering
- Educational chatbots
- Proof-of-concept LLM fine-tuning projects
- Resume and portfolio demonstration

## Tech Stack
- Python
- HuggingFace Transformers
- PEFT (LoRA)
- Gradio

## How to Run
```bash
pip install -r requirements.txt
python inference/app.py
