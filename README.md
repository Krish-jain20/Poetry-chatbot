# 📝 AI Poetry Bot using TinyLlama

This project is an AI-powered Poetry Generation Bot built using **TinyLlama**, **LoRA Fine-Tuning**, and **Hugging Face Transformers**.

The model generates poems from user prompts and refuses non-poetry-related questions.

---

# 🚀 Features

- Generate poems from user prompts
- Interactive chatbot input
- Fine-tuned TinyLlama model
- LoRA + PEFT fine-tuning
- Refusal handling for non-poetry questions
- Base vs Fine-tuned model comparison
- Similarity evaluation using NLP metrics

---

# 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- TinyLlama
- PEFT (LoRA)
- PyTorch
- BitsAndBytes
- SentenceTransformers
- ROUGE Score

---

# 📂 Project Workflow

1. Collect poetry dataset
2. Clean and preprocess data
3. Convert data into instruction format
4. Generate refusal examples
5. Merge datasets
6. Fine-tune TinyLlama using LoRA
7. Build interactive poetry chatbot
8. Compare Base vs Fine-tuned model outputs

---

# 📊 Evaluation Metrics

The project compares the Base and Fine-Tuned models using:

- Cosine Similarity
- ROUGE-1
- ROUGE-L
- Jaccard Similarity

---

# 📦 Installation

```bash
pip install transformers datasets peft accelerate bitsandbytes
pip install sentence-transformers rouge-score
