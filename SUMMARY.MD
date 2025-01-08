# Titanic Dataset Analysis

I took the dataset from Kaggle: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) using the libraries **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**. 

## Data Cleaning
I cleaned the data by filling missing values using the mean and median techniques.

## Findings

### 1. **Fare and Age are Weakly Correlated** 🤔
- **Insight**: The correlation between **Fare** and **Age** is low. This means that the fare a passenger paid doesn't strongly relate to their age. Both young and older passengers could have paid similar fares depending on their class and ticket type.

### 2. **SibSp and Parch are Moderately Correlated** 👫
- **Insight**: **SibSp** (siblings/spouses aboard) and **Parch** (parents/children aboard) show moderate correlation. Passengers with more siblings or spouses often traveled with more parents or children, indicating family travel patterns on the Titanic.

### 3. **Fare and SibSp Show a Slight Negative Correlation** 💰➡️👨‍👩‍👧‍👦
- **Insight**: There is a slight negative correlation between **Fare** and **SibSp**. Passengers with more siblings/spouses aboard might have paid slightly lower fares on average, likely due to class or ticket type chosen for family groups.

### 4. **Fare and Parch Show a Slight Negative Correlation** 💵➡️👶
- **Insight**: There is a slight negative correlation between **Fare** and **Parch**. Passengers traveling with more parents/children may have had slightly lower fares, possibly from larger family bookings in lower classes.