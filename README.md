# 🏦 Mortgage Risk Classifier

**Interpretable loan default prediction using 400K+ Fannie Mae records**

---

## 📌 Overview
This project aimed to develop a transparent, stakeholder-ready logistic regression model to predict mortgage default risk based on borrower-level loan data. Using a public Fannie Mae dataset, we engineered a binary target for 90+ day delinquency and created a pipeline that financial teams could interpret and deploy.

## 🧠 Techniques & Tools
`Logistic Regression` · `Mann-Whitney U Test` · `Chi-Square Testing` · `Upsampling` · `Feature Engineering` · `Matplotlib` · `Pandas` · `Scikit-learn`


## 📊 Key Results
- AUC of 0.83 using logistic regression with regularization
- Strongest predictors: credit score (inverse), loan-to-value, interest rate
- Found compounding risk in credit score × interest rate interactions

## 🔗 Links
- 🔍 [View Full Notebook (HTML)](rendered_html/loan_default.html)
- 🧾 [Final Report (PDF)](report.pdf)
- 🌐 [Portfolio](https://tanyanaheta.github.io)