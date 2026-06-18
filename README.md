# 🌍 NDVI-BASEED LAND COVER CLASSIFICATION USING LOGISTIC REGRESSION
A Kaggle competition project built for **Summer Analytics 2025 Hackathon**, hosted by 📊 Consulting & Analytics Club and 🤖 GeeksforGeeks. This repository tackles the challenge of classifying land cover types using **NDVI time-series satellite data** with **Logistic Regression**—despite noisy, missing, and seasonally varying data.

---

## 📁 PROJECT SUMMARY

NDVI (Normalized Difference Vegetation Index) is a crucial vegetation health indicator. Our goal is to classify land cover types—`Water`, `Impervious`, `Farm`, `Forest`, `Grass`, `Orchard`—using NDVI time-series data. Due to cloud noise and seasonal effects, feature engineering and noise handling play a vital role.

**✅ FINAL PUBLIC LEADERBOARD ACCURACY : 0.92416+**

---

## 📊 KEY TECHNIQUES USED

- 🧼 **Missing Value Imputation** using **KNN Imputer**
- 📆 **Seasonal Feature Engineering**: Mean NDVI for Winter, Spring, Summer, Fall
- 📉 **Statistical Features**: NDVI Standard Deviation across time
- ⚖️ **Balanced Logistic Regression** (Multi-class) using `class_weight='balanced'`
- 🔄 **Standard Scaling** to normalize NDVI ranges
- 📈 Model evaluation using **accuracy score** and **classification report**

---

## 🧪 NOTEBOOKS

This repo contains **two core Jupyter Notebooks**:

1. 📘 **`NDVI--Analysis-Using-Logistic-Regression.ipynb`**  
   - Full EDA (Exploratory Data Analysis)  
   - Visualization of seasonal NDVI trends and distributions  
   - Data imputation, scaling, feature engineering

2. 📘 **`NDVI CLASSIFICATION CODE (2).ipynb`**  
   - Clean and optimized competition submission code  
   - Designed for faster execution and leaderboard evaluation  

---

## 📂 DATASET INFO

- `hacktrain.csv`: Training dataset (contains noise from cloud-obscured NDVI)
- `hacktest.csv`: Testing dataset (89% noisy, 11% clean - used for leaderboard)

---

## 🛠️ TECH STACK

- Python 3.10+
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- Logistic Regression with `lbfgs` solver

---

## 🔮 FUTURE SCOPE

- Try ensemble logistic models (One-vs-Rest with regularization tuning)
- Include temporal change rate (delta NDVI) features
- Integrate PCA or TSNE for visualization

---

## 🧑‍💻 AUTHOR

**Rahul Krishna J**  
Student @ Amrita University    
Reach out: [LinkedIn](https://www.linkedin.com/in/rahul-krishna-j)

---

## 📜 LICENSE

This repository is released under the **Apache 2.0 License**.  
You are free to use, modify, and distribute the code with attribution.

---
Note : 
The soft copy of detailed version explaning the project and methodology , subjects procured to be used and problems faced and the challenges in NDVI GSI LOCATIONS DATA faced , OSM labels explanation is on process and will be shared soon in the repository , to get updates and projects on AI/ML and mini projects on PYTHON/JUPYTER NOTEBOOKS star the repo and profile mentioned under .[AUTHOR SECTION](## 🧑‍💻 AUTHOR)
No⭐ **Star this repo if it helped you!**  
🔁 Fork it to build your own NDVI analysis pipeline!
