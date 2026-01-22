# Week 16: Generative Models

## Focus: GANs Introduction

---

## Theory (3 hours)

### Theoretical Topics

- Generative vs Discriminative models
- GAN architecture
- Generator network
- Discriminator network
- Adversarial training
- GAN training challenges

---

## Practice (4 hours)

### Practical Topics

- Basic GAN implementation
- DCGAN (Deep Convolutional GAN)
- Training GANs
- Mode collapse problem
- Evaluating generated images

### Code Practice

```python
from keras.models import Sequential
from keras.layers import Dense, Reshape, Conv2DTranspose
from keras.optimizers import Adam
```

---

## Project (2 hours)

### Generate Synthetic Images

Build a GAN to generate handwritten digits.

**Dataset:** MNIST

**Steps:**

1. Load MNIST dataset
2. Build Generator network
3. Build Discriminator network
4. Implement GAN training loop
5. Train GAN
6. Generate synthetic digits
7. Visualize results

---

## Resources

- GAN papers and tutorials
- DCGAN implementations

---

## Checklist

- [ ] Understand GAN architecture
- [ ] Understand Generator and Discriminator
- [ ] Implement basic GAN
- [ ] Implement DCGAN
- [ ] Complete synthetic image generation project
