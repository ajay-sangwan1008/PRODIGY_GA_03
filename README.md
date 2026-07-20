# PRODIGY_GA_03 - Markov Chain Text Generation

## 📌 Objective

Develop a simple text generation algorithm using Markov Chains by creating a statistical language model that predicts the probability of the next word based on previous words.

---

## 📖 Project Overview

This project implements a **second-order (bigram) Markov Chain** for text generation.

The model is trained on the **TinyStories** dataset and learns transition probabilities between consecutive words. These probabilities are then used to generate new text sequences through weighted random sampling.

Unlike neural language models, Markov Chains rely only on previously observed states and transition probabilities, making them an excellent introduction to statistical text generation.

---

## ✨ Features

- Load and preprocess the TinyStories dataset
- Construct a Bigram Markov Chain
- Compute transition frequencies
- Convert frequencies into transition probabilities
- Predict the most probable next words
- Generate text using weighted probabilistic sampling
- Visualize transition probabilities

---

## 📂 Dataset

**TinyStories**

- Source: Hugging Face
- Training Samples Used: **5,000 stories**

---

## ⚙️ Workflow

1. Load TinyStories dataset
2. Clean and tokenize text
3. Build transition frequency table
4. Convert frequencies into probabilities
5. Predict next-word probabilities
6. Generate text using weighted sampling

---

## 🧠 Example

### Input

```
once there
```

### Generated Output

```
once there was a little girl who was happy to help everyone in the village...
```

---

### Next Word Prediction

| Current State | Possible Next Word | Probability |
|---------------|-------------------|------------:|
| once there | was | 0.961 |
| once there | were | 0.031 |
| once there | lived | 0.008 |

---

## 📊 Technologies Used

- Python
- Hugging Face Datasets
- Matplotlib
- Markov Chains
- Probability Theory

---

## 🚀 Learning Outcomes

- Statistical Language Modeling
- Markov Chains
- Transition Probability Estimation
- Text Generation
- Natural Language Processing Fundamentals

---

## 📌 Conclusion

This project demonstrates how probabilistic language models can generate meaningful text by learning transition probabilities between words. While Markov Chains produce locally coherent sequences, they lack long-term contextual understanding, highlighting the limitations that modern transformer-based models overcome.

---

**Internship:** Prodigy InfoTech – Generative AI Internship

Task 03: Implement Text Generation using Markov Chains.
