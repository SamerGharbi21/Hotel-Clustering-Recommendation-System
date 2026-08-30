#Hotel Clustering Recommendation System

An end-to-end Machine Learning project that analyzes hotel data, performs clustering using K-Means and DBSCAN, and provides hotel cluster predictions through an interactive Streamlit application.

---

##Project Overview

This project aims to group hotels into meaningful clusters based on multiple features such as:

- Hotel Rating
- Price
- Spa Availability
- Swimming Pool
- Room Service
- Parking
- Breakfast
- Wi-Fi
- Other hotel amenities

The clustering helps users understand hotel categories and similarities without predefined labels.

---

##Features

- ✅ Web Scraping using Selenium
- ✅ Data Cleaning & Preprocessing
- ✅ Exploratory Data Analysis (EDA)
- ✅ K-Means Clustering
- ✅ DBSCAN Clustering
- ✅ Interactive Streamlit Interface
- ✅ Saved Machine Learning Model
- ✅ Prediction using trained model

---

##Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Selenium
- Streamlit
- Matplotlib
- Plotly
- Joblib

---

##Project Structure

```text
Hotel-Clustering-Recommendation-System
│
├── notebooks/
│   ├── 01_Web_Scraping.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_KMeans.ipynb
│   └── 04_DBSCAN.ipynb
│
├── app/
│   ├── streamlit_app.py
│   └── api.py
│
├── models/
│   ├── kmeans_model.joblib
│   └── scaler.joblib
│
├── data/
├── images/
├── README.md
└── requirements.txt
```

---

##Installation

Clone the repository

```bash
git clone https://github.com/SamerGharbi21/Hotel-Clustering-Recommendation-System.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run streamlit_app.py
```

---

##Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Scaling
6. K-Means Clustering
7. DBSCAN Comparison
8. Model Saving
9. Streamlit Deployment

---

##Results

The model successfully groups hotels into meaningful clusters that can be used for recommendation systems and customer segmentation.

---

##Author

**Samer Gharbi**

Data Scientist | Machine Learning Engineer

GitHub:
https://github.com/SamerGharbi21
