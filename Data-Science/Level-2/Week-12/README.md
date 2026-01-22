# Week 12: Convolutional Neural Networks (CNN) - Part 2

## Focus: Advanced CNN & Transfer Learning

---

## Theory (3 hours)

### Theoretical Topics

- Famous architectures:
  - VGG16/VGG19
  - ResNet
  - Inception
- Transfer learning concepts
- Fine-tuning strategies
- When to use transfer learning

---

## Practice (4 hours)

### Practical Topics

- Load pre-trained models
- Transfer Learning with VGG16
- Transfer Learning with ResNet50
- Feature extraction
- Fine-tuning layers

### Code Practice

```python
from keras.applications import VGG16, ResNet50
from keras.layers import GlobalAveragePooling2D
```

---

## Project (2 hours)

### Dog vs Cat Classification

Use transfer learning for binary image classification.

**Steps:**

1. Load dog/cat dataset
2. Preprocess images
3. Load pre-trained VGG16/ResNet50
4. Freeze base layers
5. Add custom classification head
6. Train and fine-tune
7. Evaluate performance

---

## Resources

- Keras Applications documentation
- Transfer learning guides

---

## Checklist

- [ ] Understand famous CNN architectures
- [ ] Understand transfer learning
- [ ] Implement VGG16 transfer learning
- [ ] Implement ResNet50 transfer learning
- [ ] Complete Dog vs Cat project
