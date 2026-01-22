# Week 15: Autoencoders & Dimensionality Reduction

## Focus: Unsupervised Deep Learning

---

## Theory (3 hours)

### Theoretical Topics

- Autoencoder architecture
- Encoder and Decoder
- Latent space representation
- Types of autoencoders
- Denoising autoencoders
- Variational Autoencoders (VAE)

---

## Practice (4 hours)

### Practical Topics

- Vanilla Autoencoder
- Denoising Autoencoder
- Variational Autoencoder (VAE)
- Latent space visualization
- Reconstruction quality

### Code Practice

```python
from keras.layers import Input, Dense
from keras.models import Model
from keras import backend as K
```

---

## Project (2 hours)

### Image Denoising or Anomaly Detection

Choose one of the following projects:

#### Option 1: Image Denoising

1. Add noise to images
2. Build denoising autoencoder
3. Train to reconstruct clean images
4. Evaluate denoising quality

#### Option 2: Anomaly Detection

1. Train autoencoder on normal data
2. Use reconstruction error for anomaly detection
3. Identify anomalous samples

---

## Resources

- Autoencoder tutorials
- VAE papers and implementations

---

## Checklist

- [ ] Understand autoencoder architecture
- [ ] Implement vanilla autoencoder
- [ ] Implement denoising autoencoder
- [ ] Explore VAE concepts
- [ ] Complete image denoising or anomaly detection project
