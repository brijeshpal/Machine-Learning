# Machine Learning

My hands-on notebooks for learning **Python for data science and machine learning**. The repository goes from Python basics and data handling, through visualization and exploratory data analysis (EDA), to building simple ML models and analyzing real-world datasets.

---

## Notebooks

| # | Notebook | Topic | Dataset |
|---|----------|-------|---------|
| 1 | [Basics_Pandas_Numpy_Matplotlib.ipynb](Basics_Pandas_Numpy_Matplotlib.ipynb) | Python data types, NumPy, Pandas, Matplotlib | Custom data, heart disease CSV |
| 2 | [Seaborn.ipynb](Seaborn.ipynb) | Statistical visualization with Seaborn | Tips, Iris (built into Seaborn) |
| 3 | [Univariate_Bivariate_and_MultiVariate_Analysis.ipynb](Univariate_Bivariate_and_MultiVariate_Analysis.ipynb) | Univariate, bivariate and multivariate analysis | Iris |
| 4 | [EDA_Exploratory_data_Analysis.ipynb](EDA_Exploratory_data_Analysis.ipynb) | EDA, data cleaning and Logistic Regression | Titanic (Kaggle) |
| 5 | [Simple_Linear_Regression.ipynb](Simple_Linear_Regression.ipynb) | Linear Regression with scaling and cross-validation | Iris (scikit-learn) |
| 6 | [Zomato_Data_Analysis.ipynb](Zomato_Data_Analysis.ipynb) | Business-question data analysis | Zomato restaurants |

---

## What Each Notebook Covers

### 1. Python, NumPy, Pandas and Matplotlib Basics
- **Python:** booleans, logical operators, string methods, lists, sets, dictionaries (including nested ones) and tuples.
- **NumPy:** creating arrays, shape and reshape, indexing and slicing, `arange`, `linspace`, copy vs. view, boolean filtering, `ones`, and random arrays.
- **Pandas:** DataFrames, `loc` vs. `iloc`, null checks, `value_counts`, `unique`, and reading CSV files with options (`usecols`, `dtype`, `index_col`, escape characters). Also reading JSON and HTML tables, and pickling.
- **Matplotlib:** scatter plots, line plots, subplots, sine and cosine waves, bar charts, histograms, box plots and pie charts.

### 2. Seaborn
- Correlation heatmaps
- Joint plots (hex and regression)
- Pair plots, with `hue`
- Distribution plots
- Categorical plots: count plot, bar plot, box plot and violin plot

### 3. Univariate, Bivariate and Multivariate Analysis
- **Univariate:** distribution of sepal length for each Iris species.
- **Bivariate:** scatter plots of sepal and petal measurements, colored by species, using `FacetGrid`.
- **Multivariate:** pair plot of all features by species.

### 4. EDA and Logistic Regression (Titanic)
- Visualizing missing data with a heatmap.
- Survival analysis by sex, passenger class, age, siblings/spouses and fare.
- **Smart imputation:** filling missing ages with the typical age of each passenger class.
- Dropping the mostly empty `Cabin` column and one-hot encoding categorical columns.
- Training a **Logistic Regression** model to predict survival, evaluated with a confusion matrix and accuracy.

### 5. Simple Linear Regression
- Train-test split (70/30).
- Feature standardization with `StandardScaler`.
- **Linear Regression** with 5-fold cross-validation (negative MSE).
- Residual distribution plots and the R² score.

### 6. Zomato Data Analysis
A data analysis project that answers business questions from restaurant data:
1. Which type of restaurant is most common?
2. Which restaurant type gets the most votes?
3. How are ratings distributed?
4. What do couples usually spend on a meal for two?
5. Do restaurants with online ordering get better ratings than offline ones?

---

## Tech Stack

- **Language:** Python 3
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
- **Environment:** Jupyter Notebook (Anaconda)

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/brijeshpal/Machine-Learning.git
   cd Machine-Learning
   ```

2. Install the dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. Start Jupyter and open any notebook:

   ```bash
   jupyter notebook
   ```

**Datasets:** The Iris and Tips datasets load automatically from Seaborn, scikit-learn or a URL. Download the others yourself and update the file paths in the notebooks, which currently point to local folders such as `D:/Python/`:

- **Titanic:** `titanic_train.csv` from Kaggle
- **Zomato:** `Zomato data .csv`
- **Heart disease:** `heart.csv`

---

## Learning Path

If you are new to these topics, go through the notebooks in this order:

```
Python & NumPy basics → Pandas → Matplotlib → Seaborn
      → Univariate / Bivariate / Multivariate analysis
      → EDA (Titanic) → Linear Regression → Zomato case study
```

---

## Contact

**Brijesh Kumar**
- Email: [brijeshpal8878@gmail.com](mailto:brijeshpal8878@gmail.com)
- GitHub: [brijeshpal](https://github.com/brijeshpal)
- LinkedIn: [brijeshkumar8878](https://www.linkedin.com/in/brijeshkumar8878)
- Homepage: [brijeshpal.github.io](https://brijeshpal.github.io)
