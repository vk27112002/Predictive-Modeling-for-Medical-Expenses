
## 🚀 Implementation Steps

### 1. Data Loading & Cleaning
- Removed irrelevant identifiers (`person_id`)
- Handled missing values (filled with zeros)
- Verified data types and structure

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of key variables (age, BMI, etc.)
- Visualized relationships using scatter plots and histograms
- Examined categorical variables (sex, smoker status, plan type)

### 3. Feature Engineering
- Created BMI categories (Underweight, Normal, Overweight, Obese)
- Generated age groups for better segmentation
- Added chronic condition flags
- Created blood pressure status categories

### 4. Data Preparation
- Encoded categorical variables using Label Encoding
- Split data into training (80%) and testing (20%) sets
- Scaled numerical features using StandardScaler

### 5. Model Building & Evaluation
- **Models Implemented**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- **Evaluation Metrics**:
  - R² Score
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)

## 📈 Results
- **Best Model**: Random Forest Regressor
- **R² Score**: 0.98
- **Key Predictors**: Age, chronic conditions, BMI, smoker status
- **Insights**: Identified significant cost drivers for insurance pricing strategies

## 🎯 Key Insights
1. Age shows the strongest correlation with medical costs
2. Smokers incur 40-50% higher medical expenses
3. Patients with chronic conditions have significantly higher costs
4. Insurance plan type substantially affects cost distribution

## 🔧 Setup & Installation

```bash
# Clone repository
git clone (https://github.com/vk27112002/Predictive-Modeling-for-Medical-Expenses/tree/main)

# Navigate to project
cd medical-insurance-analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook Project_Insurance_Analysis.ipynb
