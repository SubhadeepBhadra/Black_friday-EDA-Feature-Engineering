# 🛍️ Black Friday EDA & Feature Engineering

## 📌 Project Description
In this project, we perform **exploratory data analysis (EDA)** along with **feature engineering** on the Black Friday dataset. We want to examine the customers' buying patterns, clean and process the data, convert features for use in machine learning, and finally get the data ready for any modeling technique.

This project showcases the whole preprocessing technique followed in real life.

---

## 🎯 Objective
A retail company needs to gain insight into how their customers behave when buying different kinds of products during the Black Friday sale.

The following attributes are available in the dataset:

- Customer demographics 
- Product categories  
- Purchase amount
- City category
- Occupation
- Marital status
- Years in current city

---

The goal is to identify key trends and develop features that will help in the **forecasting of purchase amounts**.

---

## 📂 Dataset - https://www.kaggle.com/datasets/sdolezel/black-friday
Source of dataset: Kaggle Black Friday Dataset

Dataset includes:

### Train Dataset
Includes:
- Customer information
- Product information
- Purchase amount (Target variable)

### Test Dataset
Includes:
- Customer information
- Product information
- Purchase amount unknown (To predict)

---

## 🛠 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**

---

## 🔍 Exploratory Data Analysis
Conducted extensive analysis for:

- Shape of data and dataset info
- Statistical overview
- Handling missing values
- Category wise distribution
- Customer demographics
- Purchasing trends

### Visuals Created:
- Age v/s Purchases
- Occupation v/s Purchases
- Product category v/s Purchases
- Gender based purchase analysis

### Important Findings:
> **Purchases by male customers were more compared to purchases made by females.**

## 🧹 Data Cleaning
The below operations have been carried out in this regard:

### 1. Combining Train and Test Dataset
Merging datasets to preprocess them uniformly.

### 2. Dropping Irrelevant Variables
Dropped:
- `User_ID`

### 3. Handling Null Values
Imputation of null values for:
- `Product_Category_2` - Mode Value
- `Product_Category_3` - Mode Value

### 4. Categorical Variable Encoding
Encoding:

#### Gender
- Female = 0
- Male = 1

#### Age Groups
Ordinal mapping:
- 0-17 -> 1
- 18-25 -> 2
- 26-35 -> 3
- 36-45 -> 4
- 46-50 -> 5
- 51-55 -> 6
- 55+ -> 7

#### City Category
One-Hot Encoded:
- B
- C

### 5. Preprocessing Stay Duration Feature
Transformed:
- `4+` -> `4`

Then, converted to integer datatype.

---

## ⚙️ Feature Engineering

- Label Encoding
- One-Hot Encoding
- Handling Categorical Ordinal Features
- Imputing Missing Values
- Type Conversion
- Scaling using **StandardScaler**

---

## 🤖 Data Preparation for ML
Final dataset preparation process includes:

- Features and target separation (X,y)
- Train-test split
- Dropping unnecessary feature:
  - `Product_ID`
- Scaling using:
  - `StandardScaler`

Final prepared data is now ready to train our models.

---

## 📈 Process Flow
1. Import Dataset
2. Merging Training and Testing Datasets
3. Data Cleaning
4. Handling Missing Data
5. Encoding categorical variables
6. Visualizing insights
7. Scaling features
8. Train-test split
9. Dataset ready for modeling

---

## 📌 Lessons from the Project
From this project, I learned that:

✔️ Exploratory Data Analysis
✔️ Handling missing values
✔️ Feature Engineering Techniques
✔️ Categorical variable encoding
✔️ Feature scaling
✔️ Data preparation for ML pipelines

---

## 🚀 Future ScopeFuture directions may include:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter tuning
- Model Evaluation
  
---

## 📷 Sample Analysis
Some examples of findings:
- Gender-based buying behavior
- Age-based buying behavior
- Category-wise buying behavior
- Effect of occupation on spending

---

## 👨‍💻 Author
**Subhadeep Bhadra**

Data Science / Machine Learning Project

