# Fasting-Plasma-Glucose-Level-Analysis-Using-Health-and-Lifestyle-Biomarkers

This project explores a biomedical dataset with over 50,000 records; focusing on the relationship between Fasting Plasma Glucose (FPG) levels and various clinical and lifestyle factors. It demonstrates the importance of robust preprocessing and exploratory data analysis (EDA) in understanding patterns in metabolic health.

## 📊 Key Objectives

- Prepare and clean a high-dimensional health dataset for analysis
- Explore inter-variable relationships using visual and statistical methods
- Investigate feature 'usefullnes' in determining glucose levels.

## 🔧 Core Tasks Performed

- **Extensive Data Preprocessing**:
  - Imputed missing values using both **mean imputation** (grouped by BMI) and **K-Nearest Neighbors (KNN)**.
  - Created **binned features** for Age and BMI to support stratified analysis.
  - Removed irrelevant and redundant columns to streamline the dataset.
  - Applied **outlier detection** using the Interquartile Range (IQR) method.
  - Optimized column types for better performance and clarity.

- **Data Visualization**:
  - Created **violin plots** and **scatter plots** to assess the distribution and variability of FPG levels across gender, age groups, BMI categories, and smoking/drinking status.
  - Used color-coded plots to highlight patterns in subgroups.

- **Correlation & Feature Analysis**:
  - Generated a **correlation matrix** and **heatmap** to assess relationships between FPG and other variables.
  - Engineered new features (e.g., interaction terms and ratios) to uncover hidden signals.
  - Found weak correlations overall, indicating the need for more advanced or nonlinear modeling.

## 🧰 Tools & Libraries

- **Python**
  - `Pandas`, `NumPy` – data manipulation
  - `Matplotlib`, `Seaborn` – data visualization
  - `Scikit-learn` – KNN imputation and preprocessing tools

## 📁 Repository Contents

- `fpg_analysis.ipynb` – Main Jupyter notebook with code and analysis
- `README.md` – This project overview
- `report.pdf` *(optional)* – Summary of findings and visuals

## 💡 Key Insight

Despite rigorous data cleaning and EDA, the dataset did not show strong relationships between FPG and traditional clinical or behavioral variables, suggesting a need for richer features or more complex modeling approaches in biomedical analytics.

## 👤 Author

Yash Dravid (www.linkedin.com/in/yash-dravid)

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
