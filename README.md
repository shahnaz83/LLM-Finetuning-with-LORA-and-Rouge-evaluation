### LoRA Fine-Tuning of FLAN-T5-Small for Dialogue Summarization 
A PEFT-based Lightweight LLM Training Pipeline with ROUGE Evaluation

### Overview

This project demonstrates parameter-efficient fine-tuning (PEFT) using LoRA on the FLAN-T5-Small model for dialogue summarization using the DialogSum dataset.
The goal is to show how an LLM can be adapted with only 1–2% trainable parameters, while achieving competitive summarization quality.
### Features

•	✔ Fine-tuning FLAN-T5-Small using LoRA adapters

•	✔ Only 1.7% of parameters are trained (rest are frozen)

•	✔ Evaluation using the ROUGE metric

•	✔ Clean, reproducible pipeline using HuggingFace + PEFT

•	✔ GPU-friendly (runs on Google Colab)
 

 ##### Dataset: knkarthick/dialogsum
 Task: Contains ≈ 13K dialogues + human-written summaries

# Model
Base model:

-google/flan-t5-small

Why this model?

•	Lightweight

•	Works on free Colab GPU
#### Evaluation (ROUGE)
##### Metrics reported:
1.ROUGE-1

2.ROUGE-2

3.ROUGE-L

4.ROUGE-Lsum

We evaluate both:
1.	Original FLAN-T5-Small
2.	LoRA Fine-Tuned Model

