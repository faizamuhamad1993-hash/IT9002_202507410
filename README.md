# IT9002_202507410
# Mitigating Bias and Data Protection in AI-Powered Educational Assessment Systems

## 📘 Project Overview

This repository contains an academic project developed for **IT9002 – Natural Language Processing**, focused on building and evaluating an **automated essay scoring (AES)** system using Natural Language Processing techniques.

The core emphasis of the project is on **bias mitigation** and **ethical responsibility** in AI-powered educational assessment systems. Rather than prioritizing visual exploration, the work evaluates how modeling choices and fairness-aware techniques can reduce bias while maintaining reliable performance. The project also addresses **data protection and privacy**, which are critical concerns when working with student-generated text.

---

## 🎯 Project Objectives

* Develop an NLP-based system to predict essay scores
* Evaluate baseline and bias-aware machine learning models
* Reduce bias caused by class imbalance in automated grading
* Analyze performance–fairness trade-offs in essay scoring models
* Apply ethical data handling and anonymization practices

---

## 🧠 Methods and Techniques

### Natural Language Processing

* Text cleaning and normalization
* Tokenization
* Feature extraction using **TF-IDF**

### Machine Learning Models

* **Logistic Regression** (baseline model)
* **Class-weighted Logistic Regression** (bias mitigation approach)
* **BERT (Transformer-based model)** for contextual text understanding

---

## 📊 Model Evaluation Summary

Model evaluation focuses on classification performance while accounting for fairness across score categories.

Key findings include:

* The **class-weighted Logistic Regression model** demonstrates more balanced performance across score classes compared to the baseline model
* Bias mitigation through class weighting improves fairness without a substantial loss in accuracy
* The **BERT model** achieves the strongest overall performance due to its ability to capture contextual and semantic information, though it requires higher computational resources

---

## 🔐 Bias Mitigation and Data Protection

### Bias Mitigation Strategy

* Addressed class imbalance using **class-weighted learning**
* Compared standard and fairness-aware models to assess bias reduction
* Focused on score-category bias rather than demographic visualization

### Data Protection Measures

* All essay data was **anonymized** before processing
* No personally identifiable information (PII) was used
* The project follows ethical best practices for AI in education

---

## 📂 Dataset Information

* A single essay dataset was used for training and evaluation
* The dataset was accessed strictly for academic purposes

> ⚠️ Due to privacy and licensing restrictions, the dataset is not included in this repository.

---

## 📁 Repository Structure

```
├── NLP_Project_Faiza_202507410.ipynb   # Main notebook: preprocessing, modeling, and evaluation
├── README.md                          # Project documentation
```

---

## ▶️ How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install the required dependencies:

   ```bash
   pip install numpy pandas scikit-learn nltk transformers torch
   ```
3. Download required NLTK resources:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```
4. Open and run the notebook:

   ```bash
   jupyter notebook NLP_Project_Faiza_202507410.ipynb
   ```

---

## 🔮 Limitations and Future Work

* Incorporate explicit fairness metrics in evaluation
* Explore privacy-preserving learning techniques such as federated learning
* Optimize transformer models for reduced computational cost
* Extend bias mitigation beyond class imbalance

---

## 👩‍🎓 Author

**Faiza Mohammed**
Student ID: **202507410**
Course: *IT9002 – Natural Language Processing*

---

## 📜 License and Usage

This repository is intended **solely for academic and educational purposes**. Reuse of the code or methodology should include appropriate attribution.

---

⭐ This project reflects an academic investigation into fairness, ethics, and responsible AI in educational assessment systems.

