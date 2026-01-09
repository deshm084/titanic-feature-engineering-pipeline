# 🚢 Titanic Survival: Feature Engineering Study

## 📌 Overview
While the Titanic dataset is a classic, this project focuses specifically on **Handling Missing Data** and **Feature Engineering** to improve model accuracy. I explored how socio-economic status (`Pclass`) and family dynamics (`FamilySize`) impacted survival rates.

## 🛠️ Key Techniques
* **Imputation:** Strategically filled 20% missing age data using median values to prevent data loss.
* **Feature Creation:** Engineered a `FamilySize` feature to analyze the correlation between group size and lifeboat access.
* **Encoding:** Converted categorical variables (Sex, Embarked) into dummy variables for the Random Forest Classifier.

## 📊 Findings
* **The "Wealth" Factor:** First-class passengers had a >60% survival rate, compared to <25% for third-class.
* **Gender Bias:** The model ranked `sex_male` as the most important feature, confirming the "Women and Children First" protocol.
