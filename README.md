


# 🌍 Ecological Niche Modeling under Climate Change using Ensemble Learning

## 📌 Project Overview

This project demonstrates **Ecological Niche Modeling (ENM)** using **ensemble machine learning techniques** to predict species habitat suitability under current and future climate scenarios. Synthetic environmental data are used to simulate real-world ecological responses and climate change impacts.

The model integrates multiple algorithms to improve robustness and predictive accuracy.

---

## 🎯 Objectives

* Simulate species occurrence using environmental predictors
* Train multiple machine learning models
* Build an ensemble habitat suitability model
* Project species distribution under future climate change
* Compare current vs future habitat suitability

---

## 🧠 Models Used

The ensemble consists of:

* **Random Forest**
* **Gradient Boosting**
* **Logistic Regression**

Final suitability is calculated as the **average probability** across all models.

---

## 🌡 Environmental Variables (Synthetic)

* Temperature (°C)
* Precipitation (mm/year)
* Elevation (m)
* Soil Moisture (fraction)

Future climate scenario simulates:

* +2°C temperature increase
* 10% decrease in precipitation

---

## 📊 Evaluation Metrics

* ROC AUC Score
* Ensemble AUC Performance
* Suitability distribution comparison (current vs future)

---

## 📁 Output Files

* `ecological_niche_modeling_results.xlsx`

  * Current suitability probability
  * Future suitability probability

* Suitability distribution plots

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn openpyxl
```

---

## 🚀 How to Run

```bash
python ecological_niche_ensemble.py
```

---

## 🌎 Applications

* Climate change impact assessment
* Biodiversity conservation planning
* Species range shift analysis
* Habitat suitability modeling
* Environmental decision support

---

## 📜 License

Educational and research use with synthetic data.

---

If you'd like, I can now provide a **30-word summary** that matches your project portfolio style.
