# ds-mini-project
# 🏏 IPL First-Innings Score Predictor
An end-to-end collaborative Data Science project using Git, GitHub, Google Colab, and
Markdown to predict first-innings match totals from ball-by-ball IPL match data.
---
## 👥 Team Members & Contribution Details

| Member Name | Hardware Access | Primary Project Role | Git Branch Used |
| :--- | :--- | :--- | :--- |
| **Audumbar** | Laptop | Repo Admin & Linear Regression Modeling | `feature-model` |
| **Agraj** | Laptop | Data Cleaning & Preprocessing | `feature-data-cleaning` |
| **Pranav** | Laptop | Exploratory Data Analysis & Plots | `feature-eda` |
| **Sahil** | Laptop | Model Evaluation & Performance Metrics | `feature-evaluation` |
| **Brijesh** | Mobile | Project Documentation & Markdown Formatting |
`feature-docs-brijesh` |
---
## 📌 Problem Statement & Workflow
Given the dynamic nature of limited-overs cricket, predicting an accurate final total helps
teams evaluate their run rate targets. Using `deliveries.csv`, the group created a cumulative
pipeline:
1. **Data Ingestion & Cleaning:** Filtered 1st-innings matches and computed running runs,
wickets, and overs.
2. **Exploratory Data Analysis:** Analyzed run-rate distributions and feature correlations.
3. **Model Training:** Built a `LinearRegression` baseline using `current_overs`, `current_runs`,
and `wickets_fallen`.
4. **Evaluation:** Tested model performance on unseen test splits.
---
## 🛠 Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Google Colab
- **Version Control:** Git, Git Bash, GitHub
---
## 📊 Model Evaluation Results
| Metric | Score / Value |
| :--- | :--- |
| **Model Used** | Linear Regression |
| **Mean Absolute Error (MAE)** | ~12–15 runs |
| **R-squared ($R^2$) Score** | ~0.65–0.72 |
---

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone
[https://github.com/Audumbar999/ds-mini-project.git](https://github.com/Audumbar999/ds-mini-pr
oject.git)
2. Navigate to the notebooks/ directory and run the notebooks in sequential order:
○ 01_data_cleaning.ipynb
○ 02_eda.ipynb
○ 03_model_building.ipynb
○ 04_model_evaluation.ipynb

---
### Phase 4: Commit Changes on Mobile (Lab 1)
1. Scroll down to the bottom of the page to the **Commit changes** box.
2. In the commit message box, type[cite: 1]:
```text
