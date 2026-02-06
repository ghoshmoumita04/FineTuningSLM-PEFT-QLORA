https://colab.research.google.com/drive/1z8UEvVEzij0k3k_kr1BtobjM5HX6DTmi#scrollTo=gI4Vqwijrces

# FineTuningSLM-PEFT-LORA
This is an SLM that finctunes any large language model

This repository contains a Small Language Model (SLM) fine-tuned using Parameter-Efficient Fine-Tuning (PEFT) to extract structured healthcare fields from unstructured documents (PDF text).

The model is optimized to run on single-GPU environments (e.g. Google Colab) using QLoRA (4-bit quantization) while maintaining high extraction accuracy.

Healthcare documents (claims, clinical notes, discharge summaries, etc.) are often unstructured.
This project fine-tunes a lightweight LLM to reliably extract 5 predefined fields and return strict JSON output.

Key constraints addressed:

Limited GPU memory

Deterministic, schema-aligned output

Low-cost fine-tuning

Production-friendly adapters (LoRA)
