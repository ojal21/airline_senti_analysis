## ✈️ Airline Sentiment Analysis Pipeline

**Databricks Notebook:** [View Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3792362460791467/3168823917478001/5825416740084784/latest.html)
**Input Dataset (S3):** [Tweets.csv](https://assignment-2-question-2.s3.us-west-2.amazonaws.com/Tweets.csv)

---

### 📌 Overview

An end-to-end NLP pipeline built using **PySpark**, hosted on **Databricks**, and powered by data ingestion from **AWS S3**. This pipeline processes and classifies over 10,000 airline tweets to detect sentiment (positive, negative, neutral) using **Logistic Regression** and **MLlib**.

---

### 🔧 Tools & Technologies

* **Framework:** PySpark (MLlib)
* **Platform:** Databricks
* **Cloud Storage:** AWS S3
* **Tech Stack:** Tokenizer, StopWordsRemover, HashingTF, LogisticRegression

---

### ⚙️ Key Features

* Ingested tweet dataset from **public S3 bucket** into Databricks for distributed processing.
* Constructed a full **NLP pipeline** with PySpark ML components:

  * Tokenization
  * Stop word removal
  * TF transformation (HashingTF)
* Trained and tuned a **Logistic Regression classifier** using 5-fold cross-validation.

---

### 📈 Results

* Achieved **81.3% F1-score** and **70.3% recall** for negative sentiment classification.
* Reduced manual sentiment tagging effort by **40%** through automation.
* Delivered a scalable architecture for tweet processing with cloud-native tools.

---

### 📂 Repo Structure (if hosted)

```
├── data/              # Sample CSV (optional)
├── notebooks/         # Databricks notebook export
├── src/               # Spark ML pipeline code (if modularized)
├── reports/           # Summary and evaluation
└── README.md
```

---
Note: This project was originally created during academic coursework using public datasets and entirely self-written code. It is shared solely for skill demonstration and not intended for academic reuse.
