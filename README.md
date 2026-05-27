# Harsh Mishra
 
ECE student building ML systems that solve real problems — not just Kaggle scores.
 
Currently focused on multi-modal AI, model explainability, and deploying things that actually work.
 
[Gmail](mailto:YOUR_GMAIL@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/YOUR_LINKEDIN) &nbsp;·&nbsp; [GitHub](https://github.com/HarshMishra1412)
 
---
 
## Projects
 
### The Head Counter — Multi-Modal Library Occupancy Detection
 
Fuses three independent sensing channels into a single real-time occupancy estimate for libraries. No manual counting. No single point of failure.
 
| Channel | Technique | Fusion Weight |
|---|---|---|
| Camera | YOLOv8 person detection | 25% |
| Seat sensors | Load cell → Linear Regression | 55% |
| Air quality | CO2 → Random Forest classifier | 20% |
 
Seat sensors carry the highest weight because per-seat physical measurement is the most reliable ground truth. CO2 covers blind spots cameras can't reach. Weighted fusion via `np.dot` reduces noise from any single sensor failing.
 
Output: fused count → capacity % → status (OPEN / BUSY / FULL)
 
[![View repo](https://img.shields.io/badge/View_repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HarshMishra1412/head-counter)
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-7F52FF?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
 
---
 
### Customer Churn Predictor — XGBoost + SHAP
 
End-to-end ML pipeline that identifies telecom customers about to leave, before they do. Built with a focus on business outcome, not just model accuracy.
 
| Metric | Result |
|---|---|
| Churn recall | 92% |
| ROC-AUC | 0.76 |
| Churners caught | 342 / 373 |
| Estimated revenue saved | $133,380 |
 
Key decisions: SMOTE to fix 3:1 class imbalance without data leakage. Threshold tuned from 0.5 → 0.35, recall jumped from 60% to 92%. SHAP added per-customer explainability on top of global feature importance. Customers bucketed into HIGH / MEDIUM / LOW risk tiers so retention spend goes where it matters.
 
Contract type is the strongest churn signal (importance 0.42). Converting month-to-month customers to annual contracts is the single highest-impact retention move the model reveals.
 
[![View repo](https://img.shields.io/badge/View_repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HarshMishra1412/churn-prediction-model)
&nbsp;
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-0096FF?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
 
---
 
## Stack
 
**Languages**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
 
**ML & AI**
 
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02BF8A?style=flat-square)
![YOLOv8](https://img.shields.io/badge/YOLOv8-7F52FF?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-0096FF?style=flat-square)
 
**Data**
 
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9BE8?style=flat-square)
 
**Tools**
 
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-8B0000?style=flat-square)
 
---
 
## GitHub Stats
 
<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=HarshMishra1412&show_icons=true&theme=default&hide_border=true&hide_title=true&count_private=true" />
  &nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HarshMishra1412&layout=compact&theme=default&hide_border=true" />
</p>
<p align="center">
  <img width="60%" src="https://streak-stats.demolab.com?user=HarshMishra1412&theme=default&hide_border=true" />
</p>
---
 
<sub>ECE brain. Software mindset. Every project starts with a real problem.</sub>
 
