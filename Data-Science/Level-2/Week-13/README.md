# Week 13: Recurrent Neural Networks (RNN) - Part 1

## Focus: Sequence Models & LSTM

---

## Theory (3 hours)

### Theoretical Topics

- Sequential data concepts
- RNN architecture
- Vanishing gradient in RNNs
- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

---

## Practice (4 hours)

### Practical Topics

- Simple RNN implementation
- LSTM networks
- GRU networks
- Sequence preprocessing
- Time series data handling

### Code Practice

```python
from keras.layers import SimpleRNN, LSTM, GRU
from keras.preprocessing.sequence import pad_sequences
```

---

## Project (2 hours)

### Stock Price Prediction

Build an LSTM model for stock price prediction.

**Steps:**

1. Load stock price data
2. Preprocess time series data
3. Create sequences for training
4. Build LSTM network
5. Train and predict
6. Visualize predictions

---

## Resources

- Time series datasets
- Keras RNN documentation

---

## Checklist

- [ ] Understand sequential data
- [ ] Understand RNN architecture
- [ ] Understand LSTM and GRU
- [ ] Implement LSTM network
- [ ] Complete stock prediction project
