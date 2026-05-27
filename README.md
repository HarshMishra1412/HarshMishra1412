<h1 align="center">Hey 👋 I'm Harsh Mishra</h1>
<h3 align="center">ECE Student &nbsp;•&nbsp; ML Builder &nbsp;•&nbsp; Problem Solver</h3>
 
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&center=true&vCenter=true&width=700&lines=ECE+brain+with+a+software+mindset;Multi-modal+AI+%7C+Machine+Learning+%7C+DSA;Building+things+that+actually+work.;Consistency+is+non-negotiable." />
</p>
<p align="center">
  <a href="https://github.com/HarshMishra1412">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="mailto:YOUR_GMAIL@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
---
 
## 🧠 Who Am I?
 
- 🎓 Electronics & Communication Engineering student
- 🤖 Building **real ML systems** — not just notebooks, actual deployable pipelines
- 🔌 Bridging **ECE hardware thinking** with software & AI
- 📈 Long-term mindset: discipline > motivation
- 💡 Currently exploring: multi-modal sensing, model explainability, IoT + ML
---
 
## 🚀 Featured Projects
 
### 🏛️ The Head Counter — Multi-Modal Library Occupancy Detection
 
> **Fuses camera + seat sensors + CO2 air quality into a single real-time occupancy estimate.**
 
A production-ready system that combines **3 independent sensing modalities** to detect how many people are inside a library — no manual counting needed.
 
| Channel | Model | Weight |
|---|---|---|
| 📷 Camera (YOLOv8) | Custom-trained person detection | 25% |
| 🪑 Seat sensors (Load Cell) | Linear Regression on voltage → weight | 55% |
| 🌬️ CO2 sensor | Random Forest binary classifier | 20% |
 
**Key design decisions:**
- Seat sensor carries highest weight (55%) — direct per-seat physical measurement = most reliable ground truth
- CO2 fills blind spots cameras can't cover (enclosed rooms, basements)
- Weighted fusion (`np.dot`) reduces single-sensor failure noise
```
Output: Fused count → Capacity % → Status (OPEN / BUSY / FULL)
```
 
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/HarshMishra1412/head-counter)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-purple?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
 
---
 
### 📉 Customer Churn Predictor — XGBoost + SHAP
 
> **Identifies telecom customers about to leave — before they actually do.**
 
An end-to-end ML pipeline that takes raw customer data and outputs an actionable churn probability with business-level risk tiers.
 
| Metric | Score |
|---|---|
| Churn Recall | **92%** |
| ROC-AUC | 0.76 |
| Churners caught | 342 / 373 |
| Estimated revenue saved | **$133,380** |
 
**What makes this more than just a model:**
- 🔧 **Feature engineering** — `charges_per_month`, `is_new_customer`, `has_full_protection` and more
- ⚖️ **SMOTE** — balanced 3:1 class imbalance without data leakage into test set
- 🎯 **Threshold tuning** — lowered from 0.5 → 0.35, recall jumped from 60% → 92%
- 🔍 **SHAP explainability** — per-customer prediction explanation, not just global importance
- 📊 **Risk tiers** — HIGH / MEDIUM / LOW buckets for targeted retention spend
```
Key insight: Contract type (0.42 importance) is the #1 churn driver.
Converting month-to-month → annual = single highest-impact retention move.
```
 
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/HarshMishra1412/churn-prediction-model)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-0096FF?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
 
---
 
## 🛠 Tech Stack
 
### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
 
### Machine Learning & AI
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-02BF8A?style=for-the-badge)
![Ultralytics](https://img.shields.io/badge/YOLOv8-7F52FF?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-0096FF?style=for-the-badge)
 
### Data & Visualization
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9BE8?style=for-the-badge)
 
### Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-900?style=for-the-badge)
 
---
 
## 📊 GitHub at a Glance
 
<p align="center">
  <img width="90%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HarshMishra1412&theme=tokyonight" />
</p>
<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=HarshMishra1412&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HarshMishra1412&layout=compact&theme=tokyonight&hide_border=true" />
</p>
---
 
## 🔥 Streak
 
<p align="center">
  <img width="75%" src="https://streak-stats.demolab.com?user=HarshMishra1412&theme=tokyonight&hide_border=true" />
</p>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&pause=1000&center=true&vCenter=true&width=500&lines=Showing+up+daily.;Building+habits+that+compound.;Letting+consistency+speak." />
</p>
---
 
## 📌 Philosophy
 
> **ECE brain. Software mindset. ML heart.**
>
> Every project I build has a real-world problem at its core — not just a benchmark to beat.
 
---
 
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HarshMishra1412&label=Profile+Views&color=0e75b6&style=flat" />
</p>
