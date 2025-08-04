# Credit Card Customer Attrition & Segmentation Analysis

## 📊 Project Overview

This project analyzes credit card customer data to predict customer attrition (churn) and identify distinct customer segments for targeted business strategies. Using machine learning techniques, we developed predictive models and clustering algorithms to enhance customer retention and drive business growth.

## 🎯 Business Objectives

- **Predict Customer Churn**: Identify customers likely to cancel their credit cards
- **Customer Segmentation**: Group customers into meaningful segments for targeted marketing
- **Risk Assessment**: Develop risk-value matrix for strategic decision making
- **Business Intelligence**: Provide actionable insights for retention strategies

## 📈 Dataset

- **Size**: 10,127 credit card customers
- **Features**: 23 attributes including demographics, account information, and transaction behavior
- **Target**: Attrition_Flag (Existing Customer vs Attrited Customer)
- **Data Types**: Mix of numerical and categorical variables

## 🔧 Technologies Used

- **Python**: pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Machine Learning**: Random Forest Classifier, K-Means Clustering
- **Data Visualization**: Statistical plots and business dashboards
- **Analysis**: Statistical analysis, feature engineering, model evaluation

## 🚀 Key Results

### Churn Prediction Model
- **Accuracy**: 95.5%
- **Top Predictors**: 
  - Total Transaction Amount (24.4%)
  - Total Transaction Count (21.5%)
  - Total Revolving Balance (14.0%)

### Customer Segmentation
- **4 Distinct Segments** identified:
  - **Segment 0**: High-Value Loyalists (29.3%, 15.9% churn)
  - **Segment 1**: Low-Activity Users (12.5%, 7.5% churn)
  - **Segment 2**: Regular Users (30.7%, 9.0% churn)
  - **Segment 3**: At-Risk Customers (27.6%, 28.0% churn)

## 📁 Project Structure

```
├── data/
│   └── Customer_Attrition_ClusteringSegmentation.csv
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_churn_prediction.ipynb
│   └── 03_customer_segmentation.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── visualization.py
├── results/
│   ├── model_performance.png
│   └── segment_analysis.png
└── README.md
```

## 🎨 Key Visualizations

- Customer segment distribution and churn rates
- Feature importance analysis
- Transaction behavior patterns by segment
- Risk-value matrix for business strategy

## 💡 Business Impact

### Immediate Actions
- **Segment 3**: Urgent retention campaigns (28% churn rate)
- **Segment 0**: Premium retention programs for high-value customers
- **Segment 1**: Growth activation for loyal but low-activity users

### Strategic Value
- **Revenue Protection**: Early identification of at-risk high-value customers
- **Targeted Marketing**: Segment-specific campaigns and offers
- **Resource Optimization**: Data-driven allocation of retention efforts

## 🔍 Methodology

1. **Exploratory Data Analysis**: Understanding customer behavior patterns
2. **Feature Engineering**: Selection and preprocessing of predictive variables
3. **Predictive Modeling**: Random Forest for churn prediction
4. **Clustering Analysis**: K-Means for customer segmentation
5. **Business Intelligence**: Actionable insights and recommendations

## 📊 Model Performance

| Metric | Score |
|--------|--------|
| Accuracy | 95.5% |
| Precision | 91% (Churned), 96% (Existing) |
| Recall | 80% (Churned), 98% (Existing) |
| F1-Score | 85% (Churned), 97% (Existing) |

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/faukh/credit-card-analysis.git
   cd credit-card-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis**
   ```bash
   jupyter notebook notebooks/
   ```

## 📝 Key Insights

- **Transaction behavior** is the strongest predictor of customer churn
- **Customer segments** show distinct patterns requiring different strategies
- **Early intervention** can significantly reduce churn rates
- **High-value customers** need specialized retention approaches

## 🔮 Future Enhancements

- Real-time churn scoring system
- Advanced ensemble methods (XGBoost, Neural Networks)
- Time-series analysis for seasonal patterns
- A/B testing framework for retention strategies


⭐ **If you found this project helpful, please give it a star!**
