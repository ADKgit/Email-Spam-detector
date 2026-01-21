# Spam Detection Using Machine Learning

This repository contains the implementation of a **spam detection system** developed as part of an **Applied Machine Learning coursework**.  
The project applies **supervised machine learning techniques** to classify text messages as **spam or legitimate (ham)**.

---

## Project Overview

Spam detection is a classic and highly practical machine learning problem with real-world applications in email filtering, messaging platforms, and cybersecurity.

This project implements a complete **end-to-end text classification pipeline**, including:

- Text preprocessing and cleaning
- Feature extraction from raw text
- Training supervised classification models
- Evaluating model performance using standard metrics
- Analysing strengths and limitations of the approach

The focus is on understanding the full ML workflow rather than relying on high-level automated tools.

---

## Methodology

The system follows these key stages:

### 1. Data Loading & Exploration
- Text messages and class labels are loaded
- Initial inspection of class distribution and dataset characteristics

### 2. Text Preprocessing
- Lowercasing and normalisation
- Removal of punctuation and irrelevant characters
- Tokenisation of text
- Stop-word removal
- Optional stemming / lemmatisation

These steps reduce noise and improve model generalisation.

### 3. Feature Extraction
- Text is converted into numerical representations
- Bag-of-Words and/or TF-IDF features are used
- This enables machine learning models to process textual data

### 4. Model Training
- Supervised classification models are trained on the extracted features
- The model learns patterns that distinguish spam from non-spam messages

### 5. Evaluation
- Performance is evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Results are analysed to identify false positives and false negatives

---

## Evaluation

Model performance is assessed quantitatively using classification metrics.  
This allows a balanced evaluation of how well the system detects spam while avoiding misclassification of legitimate messages.

---

## Technologies Used

- **Python**
- **NumPy**
- **pandas**
- **scikit-learn**
- **NLTK**
- **Matplotlib**
- **Jupyter Notebook**

---

## Repository Structure

```text
.
├── Task 1.ipynb        # Main notebook containing full pipeline
├── data/              # Dataset files
├── results/           # Evaluation outputs (optional)
└── README.md          # Project documentation
