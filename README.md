# 🚢 Titanic Survival Analysis  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)

A data-driven exploration of passenger survival on the Titanic. This project focuses on **cleaning**, **visualization**, and **statistical analysis** to identify key factors influencing survival rates.

## 📌 Key Features  
- **Data Cleaning**: Handled missing values (`Age`, `Embarked`), removed duplicates, and dropped irrelevant columns.  
- **Visualizations**: Interactive plots for gender distribution, age groups, survival by class, and correlation heatmaps.  
- **Statistical Tests**:  
  - T-tests for fare differences between survivors/non-survivors.  
  - Chi-square tests for gender-survival relationships.  
- **Age Group Analysis**: Categorized passengers into Child/Adult/Senior for deeper insights.

## 🛠️ Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/Titanic-Survival-Analysis.git
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_Analysis.ipynb

### 📈 Key Findings
- 🚺 Gender Bias: 74% of females survived vs. 19% of males.

- 💰 Class Matters: 63% of 1st-class passengers survived vs. 24% in 3rd class.

- 👶 Age Priority: Children had a 59% survival rate (highest among age groups).

- 🎫 Fare Correlation: Higher fares weakly correlated with survival (r = 0.26).

### 📂 Repository Structure
  Titanic-Survival-Analysis/  
├── data/                 # Raw and cleaned datasets  
├── notebooks/            # Jupyter notebooks for analysis  
├── results/              # Visualizations and charts  
├── LICENSE  
└── README.md  

### 🤝 Contributing
Contributions are welcome! Open an issue or submit a PR for:

- New visualizations

- Machine learning model integration

- Enhanced statistical analysis

### 📜 License
This project is licensed under the MIT License.

### 🙏 Acknowledgments
- Dataset: Kaggle Titanic Dataset

- Tools: Pandas, Matplotlib, Seaborn
