# Sentiment Analysis on IMDB Reviews
Sentiment classification on IMDB reviews using a hybrid CNN–BiGRU model with a custom self-attention layer, compared against a GRU baseline. Built with TensorFlow/Keras.

## Dataset
- IMDB Movie Reviews (50,000 samples)
- Binary classification: positive / negative
- Top 10,000 words, sequence length: 256

---

## Models
- **GRU Baseline** – sequential modeling using GRU
- **CNN–BiGRU–Attention** – combines CNN (local features), BiGRU (context), and attention (token importance)

---

## Results

| Model | Validation Accuracy | Loss |
|---|---|---|
| GRU Baseline | 86.31% | 0.3333 |
| CNN–BiGRU–Attention | 88.25% | 0.2795 |

Hybrid model improves accuracy by ~2%, suggesting richer feature representation through combined local and sequential modeling.

---

## Tech Stack
Python, TensorFlow/Keras

---

## Files
- `hybrid-sentiment-analysis-imdb.ipynb`
- `README.md`
