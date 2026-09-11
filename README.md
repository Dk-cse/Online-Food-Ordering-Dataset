# Online-Food-Ordering-Dataset
🍴 Online Food Ordering Dataset"What makes someone hit 'Place Order' instead of cooking tonight?"Welcome to the Online Food Ordering Dataset! This dataset captures the digital dining habits, demographics, and purchasing behaviors of modern food app users. Whether you're building machine learning models to predict customer churn, exploring target demographics, or analyzing what drives delivery satisfaction, this repository serves as your main menu.🍽️ What's on the Menu? (Features Overview)This dataset contains user demographic details, order habits, and feedback metrics. Here is a taste of the features available:Feature NameDescriptionData TypeAgeCustomer's age in yearsNumericalGenderMale / FemaleCategoricalMarital StatusSingle, Married, Prefer not to sayCategoricalOccupationStudent, Employee, Self-Employed, HousewifeCategoricalMonthly IncomeIncome bracket of the userCategorical / OrdinalEducational QualificationsHighest degree obtained (Undergraduate, Graduate, etc.)CategoricalFamily SizeNumber of individuals in the user's householdNumericalFeedbackCustomer review outcome (Positive / Negative)Categorical (Target Variable)OutputCustomer repurchase intent (Yes / No)Categorical (Target Variable)🍳 Recipe for Analysis (Key Use Cases)What can you cook up with this data?🎯 Customer Segmentation (Clustering): Group users by demographic factors (Income, Family Size, Occupation) to discover distinct buyer personas.🔮 Predictive Modeling: Train classification models (Logistic Regression, Random Forest, XGBoost) to predict customer churn or repurchase behavior based on demographic profiles.📊 Exploratory Data Analysis (EDA): Analyze how monthly income influences ordering frequency or which demographic leaves the most positive feedback.🚀 Quickstart GuideGet up and running with python in under a minute:Pythonimport pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load the dataset
df = pd.read_csv("onlinefoods.csv")

# Quick peek at the data
print(df.head())

# Visualize Feedback distribution by Occupation
plt.figure(figsize=(8, 5))
sns.countplot(data=df, x="Occupation", hue="Feedback", palette="Set2")
plt.title("Customer Feedback by Occupation")
plt.show()
📥 How to Get StartedClone the repository:Bashgit clone https://github.com/your-username/Online-Food-Ordering-Dataset.git
Install dependencies:Bashpip install pandas numpy matplotlib seaborn scikit-learn
Open notebooks/eda.ipynb and start exploring!🤝 ContributingContributions are always welcome! If you have a neat visualization, a fine-tuned model, or clean pipeline code to add:Fork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingAnalysis)Commit your Changes (git commit -m 'Add some AmazingAnalysis')Push to the Branch (git checkout -b feature/AmazingAnalysis)Open a Pull Request
