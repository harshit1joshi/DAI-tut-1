# **Exploratory Data Analysis (EDA) - Titanic Dataset 🚢**  

## **Overview**  
This repository contains an **Exploratory Data Analysis (EDA)** of the Titanic dataset from Kaggle. The analysis focuses on data cleaning, visualization, and identifying key insights related to passenger survival.  

## **Dataset**  
The dataset used in this analysis is available on Kaggle:  
👉 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  

## **Project Structure**  
```
EDA-Titanic/
│── README.md               # Project documentation
│── EDA_Titanic.ipynb       # Jupyter Notebook with EDA
│── data/                   # Folder for dataset
│   └── train.csv           # Titanic dataset (Download from Kaggle)
```

## **Steps in Analysis**  

### 📌 1. Importing Libraries  
Essential Python libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn` are used for data handling and visualization.  

### 📌 2. Data Cleaning & Preprocessing  
- Handling missing values in `Age` and `Embarked` columns  
- Dropping irrelevant columns like `Cabin`  
- Converting categorical features to numerical format  

### 📌 3. Univariate Analysis  
- Distribution of **Age**, **Pclass**, and other features  
- Identifying missing data patterns  

### 📌 4. Bivariate Analysis  
- Survival rate based on **Gender**, **Pclass**, and **Embarked**  
- Comparison of different factors influencing survival  

### 📌 5. Correlation Analysis  
- Heatmap to identify correlations between numerical features  
- Insights on which variables impact survival the most  

## **Key Insights**  
✔️ **Women had a higher survival rate compared to men**  
✔️ **Higher-class passengers had better survival odds**  
✔️ **Age played a role, with younger passengers having better survival chances**  

## **How to Use**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/EDA-Titanic.git
   cd EDA-Titanic
   ```
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook EDA_Titanic.ipynb
   ```

## **Next Steps**  
🔹 Feature engineering for better model performance  
🔹 Building ML models to predict survival  

---  
⭐ **If you find this useful, give it a star on GitHub!** ⭐  

