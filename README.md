# 🧠 No-Code Sentiment Analysis with AWS SageMaker Canvas

## Overview

This project explores how no-code machine learning platforms can be used to extract meaningful insights from customer product reviews. Using **Amazon SageMaker Canvas**, I demonstrated a complete machine learning workflow — from data ingestion to model evaluation — without writing a single line of code.

The goal was to evaluate the feasibility of no-code ML tools for rapid sentiment analysis and to understand how such platforms can support business decision-making with minimal technical overhead.

---

## 🎯 Objective

To analyze customer product reviews and classify their sentiment (Positive, Neutral, Negative) using Amazon SageMaker Canvas, enabling faster identification of customer satisfaction trends and potential areas for product improvement.

---

## 🛠 Tools & Technologies

* Amazon SageMaker Canvas
* AWS SageMaker Studio Domain
* CSV dataset (Product Reviews)
* Built-in Ready-to-Use Sentiment Model
* Quick Build Model Training

---

## 📂 Dataset

The dataset consisted of structured customer product reviews, including:

* Review Text
* Product Identifiers
* Optional metadata (ratings, categories, timestamps)

Before modeling, the dataset was reviewed to ensure:

* Clean text input
* Removal of blank or invalid entries
* Proper column selection for sentiment analysis

---

## 🔄 Workflow

1. Uploaded CSV dataset into SageMaker Canvas
2. Applied AWS’s ready-to-use Sentiment Analysis model
3. Selected target text column for sentiment detection
4. Executed Quick Build model training
5. Evaluated model predictions and confidence levels
6. Analyzed output for actionable sentiment insights

---

## 📊 Key Outcomes

* Demonstrated the viability of no-code ML for sentiment classification
* Observed efficient transformation of raw text data into sentiment categories
* Identified general customer sentiment distribution
* Highlighted how tools like SageMaker Canvas can accelerate insight generation with minimal setup effort

---

## 💡 Observations & Learnings

* No-code ML platforms significantly reduce development time for exploratory projects
* SageMaker Canvas provides an intuitive workflow suitable for rapid prototyping
* Model bias is a potential concern when relying on pre-trained models
* Clear understanding of dataset quality is still crucial for meaningful results

---

## 🌍 Real-World Applications

This workflow can be adapted for:

* HR employee satisfaction surveys
* Social media sentiment analysis
* Customer support ticket classification
* Brand monitoring and reputation analysis

---

## ⚠️ Limitations

* Limited customization of underlying model architecture
* Dependence on AWS service availability and permissions
* Less control compared to fully coded ML pipelines
* Performance highly dependent on data quality

---

## 📈 Future Improvements

* Compare Quick Build vs Standard Build model accuracy
* Integrate more diverse datasets
* Implement Python-based sentiment analysis for performance comparison
* Explore model fine-tuning and parameter control

---

## ✅ Conclusion

This project demonstrates that no-code platforms like Amazon SageMaker Canvas can serve as efficient tools for early-stage ML experimentation and business insight generation. While not a replacement for traditional data science workflows, these tools provide a powerful bridge between technical and non-technical users, enabling faster and more accessible AI-driven decision-making.

---

## 📎 Author

Fei Wang
Data & Business Analytics Enthusiast

---

Feel free to explore further enhancements or communicate with me for collaboration or feedback!
