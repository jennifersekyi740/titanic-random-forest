# Titanic Survival Analysis: Testing the "Women and Children First" Rule
## 🚢Project Overview
This project explores the Titanic passenger manifesto to determine which factors most influenced survival rates. By combining Exploratory Data Analysis (EDA) with Machine Learning, I aimed to see if social norms specifically the "women and children first" protocol were statistically evident in the survival outcomes.

## 📊 Key Insights
Through data visualization and analysis, three major trends emerged:

• The Gender Gap: Gender was the single most powerful predictor. Females had a significantly higher survival rate than males.

• The Age Factor: Children had the highest survival rates across all age groups, while seniors had the lowest.

• Social Stratification: Passenger class was a massive gatekeeper. Survival odds improved dramatically as passenger class increased (1st Class vs. 3rd Class). This is likely due to a combination of socio-economic priority and physical proximity to the boat deck, providing easier access to lifeboats compared to lower decks.

# 🛠️ Technical Stack
• Language: Python

• Libraries: Pandas (Data Manipulation), Seaborn & Matplotlib (Visualization), Scikit-learn (Modeling)

## 🤖 Modeling & Results
I compared two different classification algorithms to predict survival:
1.	Logistic Regression: Achieved 79.33% accuracy.
2.	Random Forest Classifier: Achieved 82.12% accuracy.
Conclusion: The Random Forest model performed best, likely due to its ability to capture non-linear relationships between complex features like Age, Fare, and Class. According to the feature importance plot, Sex was the primary driver of the model's predictions, followed by Fare and Pclass.

## 📁 How to Run
1.	Clone this repository.
2.	Ensure you have scikit-learn, pandas, and seaborn installed.
3.	Open Initial_Analysis_and_model_comparison.ipynb in Jupyter or Google Colab to see the full analysis.
