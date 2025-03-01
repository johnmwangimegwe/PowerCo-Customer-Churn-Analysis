# 📈 PowerCo Customer Churn Analysis 📈

## 🚀 Inspiration
The energy market is highly competitive, and customer churn is a significant challenge for utility providers like PowerCo. This project aims to uncover the factors driving churn and provide data-driven recommendations to improve customer retention.

## ⚙ What it Does
- **Data Analysis:** Explores customer data, pricing data, and churn indicators to identify patterns and trends.
- **Feature Engineering:** Creates new features such as price sensitivity, tenure, and temporal features to improve model performance.
- **Modeling:** Uses a Random Forest classifier to predict churn and evaluate the impact of various features.
- **Insights & Recommendations:** Provides actionable insights to reduce churn and improve customer retention.

## 🔧 How We Built It
- **Data Collection:** Gathered historical customer data, pricing data, and churn indicators from PowerCo.
- **Exploratory Data Analysis (EDA):** Analyzed data distributions, churn rates, and correlations between features.
- **Feature Engineering:** Created new features such as price sensitivity, tenure, and temporal features.
- **Modeling:** Trained a Random Forest classifier to predict churn and evaluated its performance using accuracy, precision, and recall.
- **Visualization:** Used Python libraries like Matplotlib and Seaborn to visualize data distributions and model results.

## 💪 Challenges We Ran Into
- **Data Skewness:** Many features were highly skewed, requiring transformations like log scaling.
- **Class Imbalance:** The churn rate was low (~10%), making it challenging to predict churn accurately.
- **Feature Importance:** Identifying the most impactful features required extensive experimentation.

## 📌 Accomplishments We're Proud Of
- Successfully identified key drivers of churn, including net margin, consumption patterns, and tenure.
- Built a predictive model with **90.5% accuracy**, though further improvements are needed for recall.
- Provided actionable recommendations to reduce churn and improve customer retention.

## 📚 What We Learned
- The importance of feature engineering in improving model performance.
- How to handle class imbalance and skewed data in predictive modeling.
- The value of domain knowledge in framing hypotheses and interpreting results.

## ⏭ What's Next for PowerCo Churn Analysis
- **Model Improvement:** Experiment with other algorithms like Gradient Boosting and XGBoost to improve recall.
- **Feature Enhancement:** Incorporate external data sources like competitor pricing and macroeconomic factors.
- **Real-Time Implementation:** Deploy the model to identify at-risk customers in real-time.
- **Continuous Monitoring:** Regularly update the model with new data to ensure accuracy.

## 🙌 Want to contribute?
If you would like to contribute to this project, please follow these steps:

### Fork the project:
- Fork the repository on GitHub.

### Clone your fork:
```bash
git clone https://github.com/johnmwangimegwe/PowerCo-Customer-Churn-Analysis.git
cd PowerCo-Churn-Analysis
```

### Create a new branch:
```bash
git checkout -b fix-issue-<ISSUE-NUMBER>
```

### Make your changes and commit them:
```bash
git add .
git commit -m "feat/docs/fix: :emoji-name: <EXPLAIN-YOUR-CHANGES>"
```

### Push your changes:
```bash
git push origin fix-issue-<ISSUE-NUMBER>
```

### Open a pull request
- Open a pull request on GitHub and fill out the template.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- Thanks to PowerCo for providing the dataset.
- Special thanks to the BCG X team for their guidance and support.
