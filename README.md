# 🌍 Greenhouse Gas Emissions – Analysis & Prediction (2010–2016)

This repository contains both **Week 1** and **Week 2** projects completed as part of the **AICTE - Skill4Future Internship Program**.

The focus of this project is on analyzing greenhouse gas (GHG) emissions across industries and building a machine learning model to predict emission factors using multi-year commodity-level data.

---

## 📌 Project Overview

### 🔹 Week 1: Greenhouse Gas Emissions Analysis (2015)
Analyze industry-wise GHG emissions from the 2015 U.S. supply chain dataset and visualize the top emission-contributing industries.

### 🔹 Week 2: Emission Prediction using Machine Learning (2010–2016)
Develop a regression model to predict **Supply Chain Emission Factors with Margins** based on descriptive metrics and data quality indicators.

---

## 📁 Project Structure

Greenhouse-Gas-Project/
├── Week1_GHG_Analysis/
│ ├── greenhouse_project.ipynb
│ ├── SupplyChainEmissionFactors2015_Summary.csv
│ └── README.md
├── Week2_GHG_Prediction/
│ ├── experiment.ipynb
│ ├── preprocessed_data.csv
│ ├── trained_model.pkl
│ └── README.md
└── Final_PPT/
└── Greenhouse_Gas_Project_Presentation.pptx

---

## 📊 Datasets Used

### 🟢 Week 1 Dataset:
- `SupplyChainEmissionFactorsforUSIndustriesCommodities2015_Summary.csv`

### 🟦 Week 2 Dataset:
- `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`  
  *(Sheets from 2010 to 2016: 2010_Detail_Commodity to 2016_Detail_Commodity)*

---

## ✅ Tasks Performed

### 🔹 Week 1 (Analysis)
- Loaded and cleaned the 2015 dataset using Pandas.
- Created new feature: **Total Emission Factor** = (Emission without margins + Margins).
- Visualized **Top 10 highest-emitting industries** using bar plots (Matplotlib, Seaborn).
- Maintained a structured and well-documented notebook.

### 🔹 Week 2 (Prediction)
- Combined data from 7 Excel sheets (2010–2016) into a single DataFrame.
- Preprocessed the data: handled missing values, label-encoded categorical columns (*Substance, Unit*).
- Selected relevant features:  
  `Substance`, `Unit`, `Reliability`, `Temporal Correlation`,  
  `Geographical Correlation`, `Technological Correlation`, `Data Collection Methodology`
- Trained a **Random Forest Regressor** using Scikit-learn.
- Evaluated model with:
  - 📉 **Mean Squared Error (MSE):** 0.0005
  - 📈 **R² Score:** 0.97
- Saved:
  - Cleaned dataset: `preprocessed_data.csv`
  - Trained model: `trained_model.pkl`

---

## 🛠️ Tools & Technologies Used

| Tool/Library      | Purpose                                 |
|-------------------|------------------------------------------|
| Python            | Core programming language                |
| Google Colab      | Development & notebook execution         |
| Pandas            | Data cleaning and transformation         |
| Matplotlib        | Basic visualizations                     |
| Seaborn           | Advanced statistical plots               |
| Scikit-learn      | Machine Learning (RandomForestRegressor) |
| Pickle            | Model serialization                      |
| GitHub            | Version control & project hosting        |

---

## 📈 Output Highlights

- **Week 1:** Bar chart of top 10 industries by total greenhouse gas emissions.  
- **Week 2:** Highly accurate ML model to predict emission factors with R² = 0.97.  
- Clean and reusable project structure with notebooks, models, and data files.

---

## 📌 Improvisations Done by Me

- Cleaned and combined multi-sheet Excel data (2010–2016).
- Engineered new columns such as total emissions for Week 1.
- Applied Label Encoding for categorical inputs to fit into ML pipeline.
- Tuned and trained Random Forest model for reliable predictions.
- Maintained and deployed the project on GitHub with proper structure.

---

## 🔚 Conclusion

This project demonstrates the application of:
- Real-world environmental data handling  
- Data visualization using Python  
- Machine learning for emission prediction  
- Deployment-ready code and models  
All work has been documented, tested, and structured for public access and future reference.

---

## 👨‍💻 Maintained by:
**Adarsh Mishra**  
📂 [GitHub Profile](https://github.com/adarsh24Hub)

