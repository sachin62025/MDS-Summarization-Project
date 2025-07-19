#  Multi-Document Abstractive Summarization on CNN/DailyMail

This project benchmarks state-of-the-art abstractive summarization models on the CNN/DailyMail dataset using Hugging Face Transformers. The models are fine-tuned and evaluated on the task of summarizing news articles into concise highlights, and compared using ROUGE-1, ROUGE-2, and ROUGE-L scores.

---

##  Objective

To implement, fine-tune, and evaluate prominent **multi-document abstractive summarization models** and benchmark them using:

- ROUGE-1 (unigram overlap)
- ROUGE-2 (bigram overlap)
- ROUGE-L (longest common subsequence)

---

## ✅ Models Implemented

| Model     | Architecture | Pretrained on | Dataset-specific checkpoint | Status       |
|-----------|--------------|---------------|-----------------------------|--------------|
| BART      | Encoder-Decoder (Transformer) | XSUM, CNN/DM | `facebook/bart-large-cnn` | ✅ Fine-tuned |
| PEGASUS   | Encoder-Decoder (Transformer) | Massive MDS pretraining | `google/pegasus-cnn_dailymail` | ✅ Fine-tuned |
| T5-Base   | Text-to-Text Transformer | Colossal Clean Crawled Corpus | `t5-base` | ✅ Fine-tuned |

---

## Result 

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/46a343e0-02e8-4ca0-b94e-921dd9a5bc7d" />
