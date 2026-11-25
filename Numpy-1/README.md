# Python Data Analysis – NumPy and Pandas

## 📌 Project Overview
This assignment focuses on developing foundational skills in Python data analysis using **NumPy and Pandas**. It covers working with numerical arrays, inspecting datasets, accessing elements, and performing basic data manipulation.

The objective is to understand how Python libraries are used to organize, manipulate, and analyze structured data as part of a Data Analyst workflow.

## 🎯 Learning Objectives

- Understand NumPy arrays and their properties.
- Explore array dimensions, shapes, and sizes.
- Perform indexing and slicing operations.
- Create and manipulate Pandas Series and DataFrames.
- Access rows and columns using integer positions.
- Understand the difference between `.loc[]` and `.iloc[]`.
- Delete rows and elements from Pandas datasets.
- Inspect and understand dataset structures.

## 🛠️ Tools and Technologies

- **Python** – Programming language
- **NumPy** – Numerical computing and array manipulation
- **Pandas** – Data manipulation and analysis
- **Jupyter Notebook** – Interactive coding environment

## 📚 Topics Covered

### 1. NumPy
- Creating NumPy arrays.
- Understanding array dimensions using `.ndim`.
- Inspecting array shapes using `.shape`.
- Finding the total number of elements using `.size`.
- Checking data types using `.dtype`.
- Accessing array elements using indexing.

### 2. Pandas
- Creating Pandas Series and DataFrames.
- Understanding DataFrame structure.
- Accessing values using integer index positions with `.iloc[]`.
- Accessing data using labels with `.loc[]`.
- Inspecting DataFrame dimensions.
- Removing rows using `.drop()`.
- Selecting rows using slicing.
- Deleting the last row without knowing its index using `df.iloc[:-1]`.

## 💻 Sample Code

**Checking the shape of a NumPy array:**

```python
temperatures_w1.shape
```

**Accessing the marks of the first-ranked student:**

```python
df.iloc[0, 2]
```

**Deleting the last row of a DataFrame:**

```python
df = df.iloc[:-1]
```

## 📂 Project Structure

```text
Python-Data-Analysis/
│
├── Python_DA_Assignment_1.ipynb
└── README.md
```

## 💡 Key Learnings

Through this assignment, I gained practical experience in:

- Working with numerical data using NumPy.
- Understanding rows, columns, and array dimensions.
- Accessing specific records using indexing.
- Manipulating structured datasets using Pandas.
- Applying basic data-cleaning techniques.
- Understanding the importance of NumPy and Pandas in data analysis.

## 🚀 Conclusion

This assignment helped strengthen my understanding of NumPy and Pandas, which are essential Python libraries for Data Analytics. These foundational concepts will support my further learning in data cleaning, exploratory data analysis (EDA), data visualization, and data-driven decision-making.

---

**Author:** Fahad  
**Focus:** Python | NumPy | Pandas | Data Analytics
