# 🤖 MachineLearning

A collection of core machine learning algorithms implemented in **Python**, covering a range of topics including regression, classification, and preprocessing. This project is ideal for beginners and intermediates looking to understand how popular ML algorithms work under the hood.

---

## 📁 Project Structure
MachineLearning/
│
├── Classification/ # 📌 Logistic regression & vectorization
├── Regression/ # 📈 Simple, multiple, and polynomial regression
├── DataPreprocessing/ # 🧹 Data cleaning, encoding, and preprocessing techniques
├── Miscellaneous/ # 🧰 Other ML utilities and helpers
└── README.md # 📄 Project documentation

---

## 🎯 Purpose

The goal of this repository is to:
- 🧠 Build fundamental ML algorithms from scratch
- 🔍 Understand vectorization, loss functions, and model training
- ⚙️ Learn data preprocessing techniques
- 📊 Visualize ML results using graphs and plots

---

## 📦 Python Libraries Used

### 📘 Scikit-learn (`sklearn`)
A popular library for machine learning tasks like classification, regression, clustering, etc.

### 🧮 NumPy
- N-dimensional array manipulation  
- Mathematical operations  
- Linear algebra, Fourier transforms, random number tools  
🔗 [GitHub](https://github.com/numpy/numpy)

### 📈 Matplotlib (`pyplot`)
- Visualizations (scatter, plot, etc.)  
- MATLAB-like interface for simplicity  
🔗 [Docs](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html)

### 🐼 Pandas
- Data structures for labeled/relational data  
- Powerful, fast, and flexible data manipulation  
🔗 [GitHub](https://github.com/pandas-dev/pandas)

---

## 📊 Data Files

### `.csv` Files
- Plain-text tabular format
- Records separated by commas
- Used for storing datasets for preprocessing and modeling

---

## 🏷️ Encoders

- **LabelEncoder:** Converts categorical text into numeric labels  
- **OneHotEncoder:** Converts labels into binary columns to avoid hierarchy assumptions

---

## ⚙️ Common ML Functions

| Function         | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| `fit()`          | Learns the model parameters                                             |
| `transform()`    | Applies learned parameters to transform the dataset                     |
| `fit_transform()`| Fits the data and transforms it in one step                             |

---

## 📈 Visualization Tools

### 🔹 `scatter()`
Creates a scatter plot  
```python
plt.scatter(x, y, color='blue', alpha=0.7)
