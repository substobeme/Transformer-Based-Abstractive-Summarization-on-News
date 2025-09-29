# 📰 Custom Transformer-Based Abstractive Summarization on News

This project implements a custom Transformer architecture for **Abstractive Text Summarization** using the **Hugging Face dataset `nlplabtdtu/xlsum_en`**.

---

## 🚀 Key Features

- ✅ Built a **Transformer model from scratch** tailored for summarization
- ✅ Implemented **two tokenization strategies**:
  - **Byte-Level BPE tokenizer**
  - **Pre-trained BART tokenizer**
- ✅ **Trainable positional encodings**
- ✅ Implemented **Greedy Search** and **Beam Search** decoding mechanisms

---

## 📊 Evaluation (ROUGE Scores)

| Epoch | Rouge-1  | Rouge-2   | Rouge-L  |
|:-----:|:--------:|:---------:|:--------:|
|   5   | 0.271596 | 0.0710721 | 0.211202 |
|  10   | 0.290982 | 0.0851596 | 0.226525 |
|  15   | 0.300244 | 0.0915641 | 0.234104 |
|  16   | 0.299387 | 0.0918897 | 0.232703 |
|  17   | 0.300989 | 0.0920619 | 0.234134 |
|  20   | 0.304150 | 0.0948534 | 0.236394 |
|  25   | 0.305513 | 0.0959938 | 0.237651 |

---

## ✅ Summary

This project showcases how a **custom Transformer**, combined with **flexible tokenization and decoding strategies**, can achieve **competitive performance** on large-scale news summarization tasks.

