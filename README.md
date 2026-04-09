📌 Overview
Introduction
Welcome to  fine-tuning large language models (LLMs)! In this hands-on guide, you will learn how to fine-tune a pre-trained language model using LLaMA-Factory, Hugging Face Transformers, and vLLM. The tutorial provides step-by-step instructions for data preparation, model fine-tuning, evaluation, and deployment.
This project provides a clean and practical implementation for fine-tuning Large Language Models (LLMs) using PEFT (Parameter-Efficient Fine-Tuning) with LoRA adapters.

Instead of fully retraining an LLM — which is costly, slow, and requires high-end GPUs — LoRA updates only a small portion of the model’s parameters. This approach enables:

Faster training

Lower memory consumption

Better performance with small datasets

Support for free or low-cost environments like Google Colab

This repository is well-suited for beginners, researchers, and developers who want to adapt powerful LLMs to their own datasets (Q&A, chat, translation, instruction-following, etc.) without heavy compute requirements.

⚙️ Tech Stack

The project is built using modern, widely adopted tools in the LLM ecosystem:

Python 3.10

Google Colab (recommended compute environment)

Hugging Face Transformers

PEFT + LoRA for efficient model fine-tuning

BitsAndBytes for 4-bit & 8-bit quantization

Hugging Face Datasets for data loading and preprocessing

These tools make it possible to run and fine-tune models like LLaMA, Mistral, and similar architectures on consumer-grade hardware.



inference.py
→ A minimal script to load the fine-tuned LoRA adapter and generate responses.
