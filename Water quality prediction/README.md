# Water Quality Prediction - RMS

This project focuses on predicting multiple water quality parameters using machine learning techniques, specifically by employing a `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month **AICTE Virtual Internship sponsored by Shell** in **June 2025**.

---

## Overview

Access to clean water is a critical global concern. Accurately predicting various water quality metrics can aid in early pollution detection and ensure timely intervention.

In this project, we:

- Collected and preprocessed real-world water quality datasets  
- Applied supervised machine learning for multi-target regression  
- Built a prediction pipeline using `MultiOutputRegressor` with `RandomForestRegressor`  
- Evaluated the model using appropriate regression metrics  

---

## Technologies Used

- **Python 3.12**
- **Pandas, NumPy** – Data handling  
- **Scikit-learn** – Machine learning modeling and evaluation  
- **Matplotlib, Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive experimentation and development  

---

## Predicted Water Quality Parameters

The model predicts the following water quality parameters:

- NH₄  
- BOD5 (BSK5)  
- Colloids  
- O₂  
- NO₃  
- NO₂  
- SO₄  
- PO₄  
- CL  

---

## Model Performance

The model was evaluated using:

- **R² Score**  
- **Mean Squared Error (MSE)**  

The performance was found to be acceptable across all predicted parameters.

---

## Model link:

```https://drive.google.com/file/d/1AQZcJuLvXvAfBgBlh0AQOTU2Dl0MgVDP/view?usp=sharing```
