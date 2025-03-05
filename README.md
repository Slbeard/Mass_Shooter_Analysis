# Mass Shooting Data Analysis

## Project Overview
This project analyzes mass shooting incidents in the United States using machine learning techniques. The goal is to identify patterns, risk factors, and potential predictors to inform policy decisions and preventive measures.

## Dataset
- **Source:** The Violence Project
- **File:** `Mass_Shooters.csv`
- **Features:** Demographics, criminal history, mental health status, incident details
- **Preprocessing:** Missing value imputation, feature selection, categorical encoding

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Data visualization and distribution analysis
   - Handling missing values
   - Identifying key trends
2. **Machine Learning Models**
   - Neural Networks (Accuracy: 12.5%)
   - Random Forest (Accuracy: 42.5%)
   - Support Vector Machine (Accuracy: 27.5%)
   - XGBoost (Best Model - Accuracy: 57.5%)
3. **Ethical Considerations**
   - Addressing potential biases in predictive policing
   - Ensuring data privacy and responsible usage

## Key Findings
- Mental health history and prior criminal activity were top predictors.
- No single predictor fully determines the likelihood of an incident.
- Data limitations impact model generalizability and accuracy.

## Future Work
- Enhance dataset by integrating socio-economic and real-time behavioral indicators.
- Improve model interpretability and fairness.
- Develop an interactive dashboard for data visualization.

## How to Use This Project
### Requirements
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `tensorflow`

### Running the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/mass-shooting-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for data analysis:
   ```bash
   jupyter notebook analysis.ipynb
   ```

---
⚠ **Disclaimer:** This project is for research purposes only. The findings should not be used for law enforcement profiling or predictive policing without proper ethical considerations.
