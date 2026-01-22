# Week 14: Recurrent Neural Networks (RNN) - Part 2

## Focus: NLP Applications

---

## Theory (3 hours)

### Theoretical Topics

- Word embeddings
- Word2Vec, GloVe
- Text preprocessing
- Tokenization
- Sequence padding

---

## Practice (4 hours)

### Practical Topics

- Text tokenization
- Padding sequences
- Embedding layers
- Sentiment analysis with LSTM
- Text classification

### Code Practice

```python
from keras.preprocessing.text import Tokenizer
from keras.preprocessing.sequence import pad_sequences
from keras.layers import Embedding, LSTM
```

---

## Project (2 hours)

### Movie Review Sentiment Analysis

Build LSTM model for sentiment analysis.

**Dataset:** IMDB Reviews

**Steps:**

1. Load IMDB dataset
2. Tokenize text data
3. Pad sequences
4. Build embedding layer
5. Build LSTM network
6. Train sentiment classifier
7. Evaluate accuracy

---

## Resources

- IMDB dataset (Keras)
- Word embeddings documentation

---

## Checklist

- [ ] Understand word embeddings
- [ ] Implement text tokenization
- [ ] Implement embedding layers
- [ ] Build LSTM for text
- [ ] Complete sentiment analysis project
