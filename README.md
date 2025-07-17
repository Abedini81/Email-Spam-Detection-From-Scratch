# Email Spam Detection from Scratch using Naive Bayes

Implementation of an email spam classifier using the **Naive Bayes** algorithm — built completely from scratch in Python, without using any machine learning libraries.  
This project is ideal for educational purposes and understanding how text classification works under the hood.

---

## Algorithm

- **Naive Bayes Classifier** (Multinomial)
- Custom implementation using:
  - Manual tokenization and preprocessing
  - Laplace smoothing
  - Log probabilities for numerical stability

---

## Dataset

- The dataset used is the classic **Spam Email** dataset (available on Kaggle).
- It contains labeled email texts as **ham (not spam)** and **spam**.

---

## Features

- Preprocessing and tokenization of raw text
- Word frequency counting by class (ham/spam)
- Prior and likelihood probability calculations
- Message prediction using log-probabilities

---

## Example Output

Input: "Get a free iPhone today, click here" Log P(Ham): -45.40 Log P(Spam): -38.77 Predicted label: spam

---

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: 
  - `pandas`  
  - `numpy`  
  - `re` (standard library)

---

## How to Run

1. Clone this repository
2. Open `EmailSpamDetection.ipynb` in Jupyter Notebook
3. Run all cells to see the training and prediction in action
