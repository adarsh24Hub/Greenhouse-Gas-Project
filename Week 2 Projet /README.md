# 🌱 Week 2 - AICTE Internship Project on Emission Prediction (2010–2016)

This project is part of **Week 2 Task** under the AICTE - Skill4Future Internship Program.  
The task was to build a **machine learning regression model** to predict:

> **Supply Chain Emission Factors with Margins**  
> using multiple years (2010–2016) of commodity-wise and industry-wise emission data.

---

## 📊 Dataset

- **File:** `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`
- **Years Covered:** 2010 to 2016
- **Sheets Used:** `2010_Detail_Commodity` to `2016_Detail_Commodity`
- **Columns:** Commodity Info, Substance, Unit, DQ Scores, Emission Factors, etc.

---

## 🛠️ Tools & Technologies Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Python       | Programming language             |
| Google Colab | Cloud-based coding environment   |
| Pandas       | Data preprocessing & manipulation |
| Scikit-learn | ML model training & evaluation   |
| Pickle       | Saving trained model             |

---

## 📈 Tasks Performed

✅ Loaded and combined data from 7 Excel sheets  
✅ Cleaned and label-encoded categorical columns  
✅ Used `RandomForestRegressor` to train model  
✅ Evaluated using MSE and R² Score  
✅ Saved:
- Cleaned data as `preprocessed_data.csv`
- Trained model as `trained_model.pkl`

---

## 🗂️ Files Included

| File Name               | Description                            |
|------------------------|----------------------------------------|
| `experiment.ipynb`     | Full notebook with all steps           |
| `preprocessed_data.csv`| Cleaned and encoded dataset            |
| `trained_model.pkl`    | Final trained ML model (Random Forest) |

---

## ✅ Output Sample

MSE: 0.0005
R² Score: 0.97

## 🔚 Conclusion

This task demonstrated the ability to:
- Work with real-world industry/commodity datasets
- Perform ML-based emission prediction using Scikit-learn
- Deploy models and datasets professionally

> 🚀 Completed as part of **AICTE - Skill4Future Internship (Week 2)**

---

📌 **Maintained by:** [Adarsh Mishra](https://github.com/adarsh24Hub)
