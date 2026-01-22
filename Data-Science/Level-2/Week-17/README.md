# Week 17: Model Deployment & MLOps

## Focus: Production-Ready Models

---

## Theory (3 hours)

### Theoretical Topics

- Model deployment concepts
- REST APIs basics
- MLOps fundamentals
- Model versioning
- Containerization basics

---

## Practice (4 hours)

### Practical Topics

- Flask basics
- FastAPI basics
- Docker basics
- Creating model API endpoints
- Model serialization (pickle, joblib)

### Code Practice

```python
from flask import Flask, request, jsonify
from fastapi import FastAPI
import joblib
import pickle
```

---

## Project (2 hours)

### Deploy a Model as Web API

Deploy one of your trained models as a web API.

**Steps:**

1. Select a trained model
2. Save model using joblib/pickle
3. Create Flask/FastAPI app
4. Create prediction endpoint
5. Test API locally
6. (Optional) Containerize with Docker
7. Document API usage

---

## Resources

- Flask documentation
- FastAPI documentation
- Docker basics

---

## Checklist

- [ ] Understand deployment concepts
- [ ] Learn Flask/FastAPI basics
- [ ] Learn Docker basics
- [ ] Create model API
- [ ] Deploy model as web service
