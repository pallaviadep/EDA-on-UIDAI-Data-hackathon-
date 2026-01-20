# EDA-on-UIDAI-Data-hackathon-
Exploratory data analysis of Aadhaar Enrollment, Demographic, and Biometric datasets using Python. This repository contains Jupyter notebooks that clean, preprocess, and analyze large-scale Aadhaar API data to extract insights at state, district, and pincode levels using pandas, NumPy, and visualization libraries.

---

## 📊 Notebooks Overview

### 1️⃣ Enrollment.ipynb
- Loads Aadhaar enrollment CSV data
- Cleans invalid and inconsistent values
- Standardizes state and district names
- Performs grouping and aggregation by:
  - State
  - District
  - Pincode
- Identifies dominant enrollment patterns
- Visualizes trends using plots

---

### 2️⃣ Demographic.ipynb
- Analyzes Aadhaar demographic data
- Processes attributes such as:
  - Gender
  - Age groups
  - Regional distribution
- Handles missing and malformed data
- Aggregates demographic metrics at multiple geographic levels
- Generates summary statistics and visual insights

---

### 3️⃣ Biometric.ipynb
- Works with Aadhaar biometric-related data
- Performs data cleaning and preprocessing
- Explores biometric update and capture trends
- Prepares data for further analysis or visualization

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** – visualizations
- **Seaborn** – statistical plots
- **Jupyter Notebook**

---

## 📁 Data Source

The datasets used in this project are Aadhaar API CSV files (e.g.):
- `api_data_aadhar_enrolment_*.csv`
- `api_data_aadhar_demographic_*.csv`
- `api_data_aadhar_biometric_*.csv`
---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/aadhaar-data-analysis.git


2. Install dependencies:
   '''bash
   
   pip install pandas numpy matplotlib seaborn


3. Open Jupyter Notebook:
   '''bash
   
   jupyter notebook
   

4. Run the notebooks in order as needed.


🎯 Purpose

- This project is intended for:

- Data cleaning and preprocessing practice

 - Exploratory analysis of government open data

 - Understanding large-scale public datasets

 - Learning pandas groupby and aggregation techniques
