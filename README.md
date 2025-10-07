# Community Wellness Initiatives for Chronic Disease Prevention

This project analyzes **chronic disease prevalence across U.S. urban communities** using predictive modeling and behavioral risk analysis.  
It combines **EDA, clustering, and machine learning (Random Forest & SVR)** to explore how **preventive care access, behavioral factors, and population characteristics** interact to shape health outcomes.

---

## 🎯 Objectives
1. Identify how preventive care access and behavioral risk factors affect chronic disease patterns.
2. Examine the role of population size and healthcare resource distribution.
3. Cluster communities by behavioral risk to target interventions.
4. Predict chronic disease burden using machine learning models.

---

## 🧰 Tech Stack
| Category | Tools / Libraries |
|-----------|-------------------|
| Data Wrangling | Python, Pandas, NumPy, Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Modeling | Random Forest, Support Vector Regression |
| Clustering | K-Means |
| Documentation | Jupyter Notebook, MS Excel, LaTeX |

---

## 📊 Key Findings
- **Behavioral factors** (smoking, inactivity, obesity, diabetes) were the strongest predictors of chronic disease.  
- **K-Means clustering** revealed that neighborhoods sharing similar risk patterns had higher disease burdens.  
- **Preventive care access alone** did not reduce disease prevalence — care effectiveness depended on socioeconomic context.  
- **Support Vector Regression (SVR)** achieved the best predictive accuracy:
  - R² = **0.9941**
  - RMSE = **0.3563**
  - MAE = **0.2435**
  - MAPE = **1.52%**

---

## 🧩 Methodology
1. **Data Cleaning** – Preprocessed CDC’s 500 Cities dataset, imputed missing values, and normalized features.  
2. **EDA** – Visualized geographic and behavioral correlations using heatmaps and scatterplots.  
3. **Feature Engineering** – Created a **Chronic Disease Index (CDI)** combining 8 major health conditions.  
4. **Modeling** – Compared Random Forest and SVR performance using standard metrics.  
5. **Clustering** – Applied **K-Means** to group tracts by behavioral profiles and examined their CDI distribution.  
6. **Feature Importance** – Identified top predictive factors (inactivity, smoking, obesity).  

---

## 🧩 Model Comparison
| Model | R² | RMSE | MAE | MAPE |
|--------|----|------|-----|------|
| Random Forest | 0.9901 | 0.4612 | 0.3429 | 2.05% |
| SVR | **0.9941** | **0.3563** | **0.2435** | **1.52%** |

---

## 🌍 Data Source
- [CDC 500 Cities Dataset (2018)](https://chronicdata.cdc.gov)
- [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss)
- [World Health Organization (WHO) – Noncommunicable Diseases](https://www.who.int/news-room/fact-sheets/detail/noncommunicable-diseases)

---

## 📄 Report
The complete research report is available as a PDF:  
📘 **Community_Wellness_Initiatives_for_Chronic_Disease_Prevention.pdf**

---

## 📈 Sample Visualization
*(Add your chart here, e.g., correlation heatmap or model prediction scatter plot)*  
```markdown
![Feature Importance](assets/feature_importance.png)
