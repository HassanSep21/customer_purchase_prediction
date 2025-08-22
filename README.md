# 📌 Shopping Purchase Prediction

> A machine learning classifier that predicts whether online shopping sessions will result in purchases using k-nearest neighbors algorithm.

---

## ✨ Features

- ✅ **Smart Data Processing** - Automatically converts and normalizes 17 different session features including page views, durations, and user behavior metrics
- ✅ **K-Nearest Neighbors Classification** - Uses k=1 KNN algorithm for accurate purchase prediction based on session similarity
- ✅ **Comprehensive Evaluation** - Provides detailed performance metrics including sensitivity, specificity, and accuracy rates
- ✅ **Month Conversion** - Intelligently converts month abbreviations to numerical indices for better model performance
- ✅ **Visitor Type Analysis** - Distinguishes between returning and new visitors to improve prediction accuracy

---

## 🛠 Tech Stack

- **Languages:** Python
- **Libraries:** scikit-learn, csv, sys
- **Machine Learning:** K-Nearest Neighbors (KNN) Classification
- **Data Processing:** CSV parsing with automatic type conversion

---

## 📊 Data Features

The model analyzes 17 key features from shopping sessions:

- **Page Metrics:** Administrative, Informational, and Product-related page views and durations
- **Behavior Analytics:** Bounce rates, exit rates, and page values
- **Session Context:** Special days, months, operating systems, browsers
- **User Profiles:** Visitor type (returning vs new), weekend sessions
- **Technical Data:** Region, traffic type for demographic insights

---

## 🚀 Quick Start

1. **Prepare your data** - Ensure your CSV file contains all required columns with proper headers
2. **Run the classifier:**
   ```bash
   python shopping.py your_data.csv
   ```
3. **View results** - Get instant feedback on model performance with accuracy metrics

---

## 📈 Output Metrics

- **Accuracy:** Number of correct vs incorrect predictions
- **True Positive Rate (Sensitivity):** Percentage of actual purchases correctly identified
- **True Negative Rate (Specificity):** Percentage of non-purchases correctly identified

---

## 🎯 Use Cases

Perfect for e-commerce businesses looking to:
- Optimize marketing campaigns by identifying high-intent sessions
- Improve website conversion rates through behavioral insights
- Personalize user experiences based on purchase likelihood
- Analyze seasonal shopping patterns and trends