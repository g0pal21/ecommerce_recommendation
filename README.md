# E-commerce Recommendation System

This repository contains a Recommendation System for an e-commerce platform built using Python. The goal is to suggest personalized products to customers based on their interactions, leveraging collaborative filtering and content-based techniques. This system aims to enhance customer experience by making accurate and insightful recommendations.

## Features

Here are the key features of this Recommendation System:

✅ User-based collaborative filtering for personalized recommendations
✅ Item-based collaborative filtering using product similarity
✅ Data preprocessing techniques to clean and prepare data
✅ Evaluation metrics like RMSE to assess model performance
✅ Visualizations and insights into product relationships and customer behaviors

## 🧠 Approach

### 📂 Data Loading & Preprocessing

* Reads transaction or ratings data
* Cleans missing/invalid entries
* Converts data into a user-item interaction matrix

### 🤖 Recommendation Model

* Uses collaborative filtering techniques to recommend items:

  * User-User Similarity
  * Item-Item Similarity
* Generates top-N recommendations for each user

### 📈 Evaluation

* Evaluates the system using RMSE
* Provides quantitative analysis of model performance

## 🛠️ Tech Stack

* 🐍 **Language**: Python 3.x
* 📓 **Notebook**: Jupyter Notebook
* 📊 **Libraries**:

  * `numpy==1.24.3`
  * `pandas==1.5.3`
  * `scikit-learn==1.2.2`
  * `matplotlib==3.7.1`
  * `seaborn==0.12.2`

## ⚙️ Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/g0pal21/ecommerce_recommendation.git
cd ecommerce_recommendation
pip install -r requirements.txt
```

