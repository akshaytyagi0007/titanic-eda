# 🚢 Titanic Survival EDA

Exploratory Data Analysis on the famous Titanic dataset using Python, Seaborn, and Matplotlib. This project visually explores key factors that influenced passenger survival during the Titanic disaster.

---

## 📌 Objective

To analyze and visualize the Titanic dataset and answer questions like:
- Did women survive more than men?
- Did first-class passengers have a better chance of survival?
- How did age affect survival?
- Did family size impact survival rate?

---

## 📁 Project Structure

```
titanic-eda/
│
├── Titanic.ipynb       # Main Jupyter Notebook with all analysis
├── train.csv           # Titanic dataset (from Kaggle)
└── README.md           # Project documentation
```

---

## 📊 Dataset

The dataset used is the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).

| Column | Description |
|--------|-------------|
| `Survived` | 0 = No, 1 = Yes |
| `Pclass` | Passenger class (1st, 2nd, 3rd) |
| `Sex` | Male or Female |
| `Age` | Age of the passenger |
| `SibSp` | Number of siblings/spouses aboard |
| `Parch` | Number of parents/children aboard |
| `Fare` | Ticket fare paid |
| `Embarked` | Port of embarkation |

---

## 📈 Visualizations

### 1. Survival Rate by Gender
- Bar plot comparing survival rate between male and female passengers
- **Finding:** Female survival rate (~74%) was nearly 4x higher than male (~19%)

### 2. Survival Rate by Passenger Class
- Bar plot showing survival rate across 1st, 2nd, and 3rd class
- **Finding:** 1st class passengers had the highest survival rate (~63%)

### 3. Survival Rate by Age
- Stacked histogram showing age distribution of survivors vs non-survivors
- **Finding:** Children had slightly better survival chances than adults

### 4. Fare Distribution by Class and Survival
- Box plot of ticket fare grouped by class and survival status
- **Finding:** Higher fare payers in 1st class had better survival odds

### 5. Survival Rate by Family Size
- Bar plot of survival rate based on number of family members aboard
- **Finding:** Small families (2-4 members) survived more than solo travelers or large families

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ⚙️ How to Run

1. Clone the repository
```bash
git clone https://github.com/akshaytyagi0007/titanic-eda
cd titanic-eda
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and place `train.csv` in the project folder

4. Launch Jupyter Notebook
```bash
jupyter notebook Titanic.ipynb
```

---

## 💡 Key Findings

| Factor | Insight |
|--------|---------|
| **Gender** | Women survived at 74%, men at only 19% |
| **Class** | 1st class: 63%, 2nd class: 47%, 3rd class: 24% |
| **Age** | Children had relatively better survival chances |
| **Fare** | Higher fare correlated with better survival |
| **Family Size** | Family size of 3 had the best survival rate |

---

## 👨‍💻 Author

**Your Name**
- GitHub — [@akshaytyagi0007](https://github.com/akshaytyagi0007)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
