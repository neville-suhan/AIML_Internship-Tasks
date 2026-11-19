# AI/ML Internship Assessment Tasks

This repository contains my solutions for the AI/ML internship assessment.

## Task 1: Fine-Tuning with LoRA/QLoRA
- Fine-tuned Qwen2.5-0.5B-Instruct using QLoRA.
- Used the SST-2 sentiment analysis dataset.
- Compared the base model and fine-tuned model on a held-out test set.
- Included training settings, evaluation results, and failure analysis.

## Task 2: Retrieval-Augmented Generation (RAG)
- Built a RAG pipeline from scratch using the NIST AI Risk Management Framework document.
- Used text chunking, sentence embeddings, and FAISS for retrieval.
- Compared retrieval performance using two chunk sizes.
- Included test questions, retrieval evaluation, and failure analysis.

## Task 3: Model Optimisation
- Compared FP16 and 4-bit quantization using Qwen2.5-0.5B-Instruct.
- Evaluated GPU memory usage, generation speed, and answer quality.
- Included explanations of quantization and KV cache.
- Proposed a deployment approach for 20 simultaneous users on a 24 GB GPU.

## Technologies Used
- Python
- Google Colab
- Hugging Face Transformers
- PEFT and BitsAndBytes
- Sentence Transformers
- FAISS
- PyTorch
- NumPy

## Repository Structure
- `Task_1_LoRA_Fine_Tuning/` – Fine-tuning notebook
- `Task_2_RAG/` – RAG notebook and evaluation results
- `Task_3_Model_Optimisation/` – Model optimisation notebook
- `Internship_Report.pdf` – Combined assessment report

Each task folder contains its corresponding implementation and results.
