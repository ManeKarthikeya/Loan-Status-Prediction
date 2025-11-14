# 🏦 Loan Status Prediction - Machine Learning Credit Risk Assessment

## 🎯 Project Overview

A **comprehensive machine learning solution** that predicts loan approval status based on applicant financial and demographic data. This system helps financial institutions automate and standardize credit risk assessment using **Support Vector Machine (SVM)** classification.

## 📈 Dataset Features

### 👤 Applicant Demographics
- **Gender**: Male (1) or Female (0)
- **Marital Status**: Married (1) or Not Married (0)
- **Dependents**: Number of dependents (0, 1, 2, 4 for '3+')
- **Education**: Graduate (1) or Not Graduate (0)
- **Employment**: Self-Employed (1) or Not Self-Employed (0)

### 💰 Financial Information
- **Applicant Income**: Primary income of the applicant
- **Coapplicant Income**: Secondary income source
- **Loan Amount**: Requested loan amount
- **Loan Amount Term**: Duration of the loan
- **Credit History**: Creditworthiness (1.0 = meets guidelines, 0.0 = otherwise)

### 🏠 Property & Location
- **Property Area**: Rural (0), Semiurban (1), or Urban (2)

### 🎯 Target Variable
- **Loan_Status**: Loan approval status (1 = Approved, 0 = Not Approved)

## 🤖 Machine Learning Implementation

### 🔍 Algorithm Used
- **Support Vector Machine (SVM)**: Linear kernel for binary classification
- **Stratified Sampling**: Maintains class distribution in train-test splits
- **Data Preprocessing**: Comprehensive cleaning and encoding

### 📊 Model Performance
- **Training Accuracy**: High predictive performance on training data
- **Test Accuracy**: Strong generalization on unseen loan applications
- **Financial Reliability**: Suitable for credit risk assessment

## 🛠️ Technical Implementation

### Data Science Pipeline
1. **Data Collection & Cleaning**: Handling missing values and data validation
2. **Exploratory Data Analysis**: Statistical insights and visualization
3. **Feature Engineering**: Categorical encoding and data transformation
4. **Model Training**: SVM implementation with optimal parameters
5. **Performance Evaluation**: Accuracy metrics on both datasets
6. **Prediction System**: Interactive loan status prediction

### Technology Stack
- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Scikit-learn**: SVM algorithm and metrics
- **Matplotlib & Seaborn**: Advanced data visualization

## 🎨 Data Visualization

### 📊 Education vs Loan Status Analysis
- **Dark Scientific Theme**: Professional black background with neon colors
- **Count Plot Visualization**: Comparative analysis of education levels
- **Glow Effects**: Enhanced visual appeal with path effects
- **Neon Color Palette**: Cyan and red for approved/rejected status

### 🔍 Correlation Insights
- Visual patterns between education levels and loan approval rates
- Demographic factor impact on lending decisions
- Statistical relationships in financial data

## 🚀 Quick Start

### Prerequisites
```bash
python >= 3.8
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Installation & Usage

1. **Clone the repository**:
```bash
git clone https://github.com/ManeKarthikeya/Loan-Status-Prediction.git
cd Loan-Status-Prediction
```

2. **Run the prediction system**:
```bash
python loan_status_prediction.py
```

3. **Input applicant details** when prompted:
   - Gender, Marital Status, Dependents
   - Education and Employment status
   - Financial information and credit history
   - Property area details

### Example Usage
```python
# The script will prompt for:
# Gender (1 for Male, 0 for Female)
# Married status (1 for Yes, 0 for No)
# Dependents (0, 1, 2, or 4 for '3+')
# Education (1 for Graduate, 0 for Not Graduate)
# Self_Employed status (1 for Yes, 0 for No)
# ApplicantIncome, CoapplicantIncome
# LoanAmount, Loan_Amount_Term
# Credit_History (1.0 or 0.0)
# Property_Area (0, 1, 2)

# Output: "Loan Approved" or "Loan Not Approved"
```

## 📁 Project Structure

```
Loan-Status-Prediction/
├── loan_status_prediction.py     # Main prediction script
├── loan_dataset.csv              # Loan application dataset
└── README.md                     # Project documentation
```

## 📊 Dataset Information

- **Samples**: Cleaned loan application records
- **Features**: 11 applicant and financial characteristics
- **Target**: Binary loan approval status
- **Data Quality**: Preprocessed with handled missing values

## 🎯 Use Cases

### 🏦 **Financial Institutions**
- Automated loan application processing
- Credit risk assessment standardization
- Loan officer decision support
- Regulatory compliance monitoring

### 📈 **Risk Management**
- Default probability estimation
- Portfolio risk analysis
- Lending strategy optimization
- Customer segmentation

### 🎓 **Educational Value**
- Support Vector Machine (SVM) classification examples
- Financial machine learning applications
- Data preprocessing techniques
- Model evaluation in finance

## ⚠️ Important Notes

- **Educational Purpose**: This is a demonstration project for machine learning concepts
- **Real-world Considerations**: Actual loan decisions involve more complex factors and regulatory requirements
- **Bias Awareness**: Machine learning models can perpetuate existing biases in historical data
- **Professional Use**: Always consult financial experts and comply with lending regulations
