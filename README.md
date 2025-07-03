# 🏅 Olympic Medal Prediction — Beginner ML Project

## 📌 Project Overview

This is a beginner-level machine learning project using Python and Jupyter Notebook. It includes creating a hypothesis, preparing the model, and measuring error.

We use data from historical Olympic Games to try to predict how many medals a country will win based on historical and current data.

---

## 🚀 Project Steps

1. Form a hypothesis  
2. Find and explore the data  
3. Reshape the data to predict the target  
4. Clean the data for ML  
5. Pick an error metric  
6. Split the data  
7. Train a model  

---

## ⚙️ Setup

- **Hypothesis**:  
  *“We can predict how many medals a country will win in the Olympics.”*

- **Error Metric**: Mean Absolute Error (MAE).

- **Data Splitting**:  
  The dataset is split into **training data** and **test data**.  
  The model is trained using the training data and evaluated using the test data.

- **Model**:
  
  $Y = a_1 \times x_1 + a_2 \times x_2 + B$
  
  Where:  
  - **x₁**: Number of athletes a country has entered into the Olympics  
  - **x₂**: Number of medals won by the country in the previous Olympics  

---

## 📝 Note

**Python packages used**:
- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`

The file **taems.csv** contains the data and has been uploaded to this repository.

---

## 🔎 Insights

- The model performs well if a country sends many athletes to the Olympics.
- The model performs poorly if a country sends only a few athletes.
