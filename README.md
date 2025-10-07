Chat Reply Recommendation (Offline AI)

This project builds a small AI that chats back — it learns how to reply like a human using Transformers (GPT-2 / DistilGPT-2), all running offline in a Jupyter Notebook.

---

What It Does
- Reads chat pairs between two users  
- Learns reply patterns from past conversations  
- Predicts the next message in the chat  
- Evaluates itself using BLEU, ROUGE, and Perplexity

---

Tech Stack
Python, PyTorch, Transformers, Datasets, NLTK, Evaluate

---
 How to Run
```bash
pip install transformers datasets torch nltk evaluate
jupyter notebook
