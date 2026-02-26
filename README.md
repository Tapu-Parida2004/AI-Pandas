# 🐼 Complete Pandas Syllabus for AI & ML

> Structured roadmap from Beginner → Advanced → Real-World Projects  
> Designed specifically for AI / ML job preparation.

---

# 🔹 PHASE 1: Foundations (Beginner Level)

## 1️⃣ Introduction to Pandas

- What is Pandas?
- Why Pandas is important in AI/ML
- Installing Pandas
- Importing Pandas
- Pandas vs NumPy
- Series vs DataFrame

---

## 2️⃣ Pandas Data Structures

- Creating Series
- Creating DataFrame

### Create From:
- List
- Dictionary
- NumPy array
- CSV file

### Concepts:
- Data types in Pandas
- Index and Columns

---

## 3️⃣ Data Inspection

- `.head()`
- `.tail()`
- `.info()`
- `.describe()`
- `.shape`
- `.columns`
- `.dtypes`
- `.value_counts()`
- `.unique()`

---

# 🔹 PHASE 2: Data Selection & Filtering

## 4️⃣ Selecting Data

- Selecting columns
- Selecting multiple columns
- Row selection
- `.loc[]`
- `.iloc[]`
- Boolean indexing
- Conditional filtering
- `query()` method

---

## 5️⃣ Indexing & Reindexing

- Setting index
- Resetting index
- Multi-index
- `sort_values()`
- `sort_index()`

---

# 🔹 PHASE 3: Data Cleaning (🔥 Very Important for ML)

## 6️⃣ Handling Missing Values

- `isnull()`
- `notnull()`
- `dropna()`
- `fillna()`
- Forward fill / backward fill
- Replacing values

---

## 7️⃣ Handling Duplicates

- `duplicated()`
- `drop_duplicates()`

---

## 8️⃣ Data Type Conversion

- `astype()`
- `to_datetime()`
- `to_numeric()`
- Category data type

---

## 9️⃣ String Operations

- `.str.lower()`
- `.str.upper()`
- `.str.contains()`
- `.str.replace()`
- `.str.split()`

---

# 🔹 PHASE 4: Data Manipulation

## 🔟 Column Operations

- Creating new columns
- Renaming columns
- Dropping columns
- Apply function on column

---

## 1️⃣1️⃣ Apply & Lambda

- `.apply()`
- `.map()`
- `.applymap()`
- Lambda functions

---

## 1️⃣2️⃣ GroupBy (🔥 VERY IMPORTANT FOR ML)

- `groupby()`

### Aggregations:
- `mean()`
- `sum()`
- `count()`
- `agg()`
- Multiple aggregations

### Concepts:
- Transform vs Aggregate

---

# 🔹 PHASE 5: Data Combining (Feature Engineering Power)

## 1️⃣3️⃣ Merging & Joining

- `merge()`
  - inner
  - left
  - right
  - outer
- `join()`
- `concat()`

---

# 🔹 PHASE 6: Time Series (Important for AI)

## 1️⃣4️⃣ Working with Dates

- Datetime conversion
- Extracting:
  - year
  - month
  - day
  - weekday

### Time Operations:
- Resampling
- Rolling window
- Expanding window

---

# 🔹 PHASE 7: Advanced Pandas for ML

## 1️⃣5️⃣ Pivot Tables

- `pivot()`
- `pivot_table()`
- `crosstab()`

---

## 1️⃣6️⃣ Window Functions

- Rolling mean
- Rolling sum
- Expanding mean

---

## 1️⃣7️⃣ Performance Optimization

- Vectorization
- Avoid loops
- Memory usage optimization
- Using categorical data

---

# 🔹 PHASE 8: Pandas for Machine Learning Workflow

## 1️⃣8️⃣ Exploratory Data Analysis (EDA)

- Correlation matrix
- Outlier detection
- Distribution analysis
- Feature importance preparation

---

## 1️⃣9️⃣ Feature Engineering

- Creating new features
- Encoding categorical variables
- Binning
- Scaling preparation

---

## 2️⃣0️⃣ Preparing Data for ML Models

- Splitting features and target
- Handling imbalance
- Exporting cleaned dataset

### Integration With:
- NumPy
- Scikit-learn

---

# 🔹 PHASE 9: Real-World Project Practice

Practice with:

- Kaggle datasets
- Titanic dataset
- House Price prediction
- Sales forecasting dataset

---

## Build:

- Data cleaning pipeline
- Feature engineering pipeline
- EDA report

---

# 🔥 Industry-Level Topics (AI Job Ready)

- Writing reusable data cleaning functions
- Automating preprocessing
- Handling large datasets
- Pandas + SQL integration
- Pandas + Matplotlib / Seaborn
- Pandas profiling
- Working with JSON & APIs

---

# 🗓 Suggested 30-Day Learning Timeline

| Week | Focus |
|------|--------|
| Week 1 | Basics + Selection |
| Week 2 | Cleaning + Manipulation |
| Week 3 | GroupBy + Merge + Time Series |
| Week 4 | Feature Engineering + Projects |

---

# 🎯 After Completing This Roadmap

You will be able to:

- ✅ Clean messy real-world datasets
- ✅ Perform complete EDA
- ✅ Build ML-ready datasets
- ✅ Create features for AI models
- ✅ Handle 90% of data preprocessing tasks in interviews

---

# 🚀 Next Steps

You can now add:

- 📅 Daily structured 20-day plan
- 💻 Practice question sets
- 📊 Interview Q&A on Pandas
- 🔥 Mini projects for AI job prep
- 🧠 Advanced Pandas for Data Science interviews

---

# 📘 1️⃣ Introduction to Pandas (AI/ML Job-Ready Depth)

> Absolute Foundation → Industry-Level Understanding  
> Pandas is the backbone of Data Preprocessing in Machine Learning.

---

# 🔹 What is Pandas?

## ✅ Definition

Pandas is a powerful Python library used for:

- Data manipulation  
- Data analysis  
- Data cleaning  
- Data preprocessing  

It provides **fast, flexible, and expressive data structures**.

### 📌 Name Meaning

**Pandas = Panel + Data + Analysis**

---

# 🔹 Who Created Pandas?

Pandas was created by  
👉 **Wes McKinney** in 2008.

It is now maintained by the open-source community under **PyData**.

---

# 🔹 Why Pandas Was Created?

Before Pandas:

- Data cleaning in Python was difficult  
- NumPy handled only numerical arrays  
- No easy tabular structure like Excel  

Pandas introduced:

- ✅ **Series (1D labeled data)**
- ✅ **DataFrame (2D table like Excel/SQL)**

---

# 🔥 Why Pandas is Important in AI/ML?

AI/ML is NOT model-first.

It is:

```
Raw Data → Clean Data → Feature Engineering → Model → Prediction
```

👉 80% of real-world ML work = Data cleaning & preprocessing

That is where Pandas dominates.

---

# 🔹 Real AI/ML Workflow

```
CSV File
   ↓
pandas.read_csv()
   ↓
Data Cleaning
   ↓
Handling Missing Values
   ↓
Encoding Categorical Data
   ↓
Feature Engineering
   ↓
Convert to NumPy
   ↓
Train Model (Scikit-learn / TensorFlow / PyTorch)
```

---

# 🔹 Where Pandas is Used in ML?

| Task | Pandas Role |
|------|-------------|
| Data Cleaning | Remove nulls, duplicates |
| Feature Engineering | Create new features |
| Data Transformation | Normalize, encode |
| EDA | Analyze trends |
| Dataset Splitting | Prepare X and y |
| Aggregation | Group statistics |

---

# 🔹 Installing Pandas

### 🔸 Using pip

```bash
pip install pandas
```

### 🔸 Using conda

```bash
conda install pandas
```

---

# 🔹 Checking Installation

```python
import pandas as pd

print(pd.__version__)
```

Example Output:

```
2.2.1
```

---

# 🔹 Importing Pandas

Standard convention:

```python
import pandas as pd
```

Why `pd`?

- Short  
- Standard practice  
- Used in official documentation  

---

# 🔹 Pandas vs NumPy (🔥 Interview Important)

## 🔷 NumPy

- Works with arrays  
- Only numeric data  
- Faster for mathematical computation  
- No column names  

Example:

```python
import numpy as np

arr = np.array([10, 20, 30])
print(arr)
```

Output:

```
[10 20 30]
```

---

## 🔷 Pandas

- Works with labeled data  
- Handles numeric + text + mixed data  
- Has column names  
- Built on top of NumPy  

Example:

```python
import pandas as pd

data = pd.Series([10, 20, 30])
print(data)
```

Output:

```
0    10
1    20
2    30
dtype: int64
```

Notice:

- Has index  
- Has dtype  
- Structured display  

---

# 🔥 Comparison Table

| Feature | NumPy | Pandas |
|----------|--------|---------|
| Data Type | Homogeneous | Heterogeneous |
| Structure | Array | Table |
| Column Names | ❌ | ✅ |
| Best For | Mathematical ops | Data analysis |
| Built On | C | NumPy |

---

# 🔹 Visual Diagram

## NumPy Array

```
[ 1  2  3  4 ]
```

## Pandas DataFrame

```
+----+-------+-------+
| ID | Name  | Score |
+----+-------+-------+
| 1  | A     | 90    |
| 2  | B     | 85    |
+----+-------+-------+
```

---

# 🔹 Series vs DataFrame (CORE FOUNDATION)

---

## 🟢 What is a Series?

A **Series** is:

> 1-dimensional labeled array

Think of it as:

- Single Excel column  
- Single feature in ML  

### Example

```python
import pandas as pd

marks = pd.Series([90, 85, 88, 92])
print(marks)
```

Output:

```
0    90
1    85
2    88
3    92
dtype: int64
```

---

### Custom Index

```python
marks = pd.Series([90, 85, 88], index=["Math", "Physics", "Chemistry"])
print(marks)
```

Output:

```
Math        90
Physics     85
Chemistry   88
dtype: int64
```

Now it behaves like:

👉 Dictionary + Array combined

---

## 🟢 What is a DataFrame?

A **DataFrame** is:

> 2-dimensional labeled data structure

Think of it as:

- Excel sheet  
- SQL table  
- ML dataset  

---

### Example

```python
import pandas as pd

data = {
    "Name": ["Aman", "Riya", "John"],
    "Age": [22, 21, 23],
    "Score": [88, 92, 85]
}

df = pd.DataFrame(data)
print(df)
```

Output:

```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
```

---

# 🔥 Visual Understanding

### Series

```
0 → 88
1 → 92
2 → 85
```

### DataFrame

```
+----+-------+-----+-------+
|    | Name  | Age | Score |
+----+-------+-----+-------+
| 0  | Aman  | 22  | 88    |
| 1  | Riya  | 21  | 92    |
| 2  | John  | 23  | 85    |
+----+-------+-----+-------+
```

---

# 🔹 Internally How DataFrame Works

DataFrame = Collection of Series

```
DataFrame
   |
   |-- Series (Name column)
   |-- Series (Age column)
   |-- Series (Score column)
```

---

# 🔥 In ML Terms

If dataset is:

```
Age   Salary   Bought
22    25000    0
35    60000    1
```

Then:

- DataFrame = Full dataset  
- Series = Single feature (Age)  
- Series = Target variable (Bought)  

---

# 🔹 Memory Insight (Advanced Concept)

Pandas uses:

- NumPy arrays internally  
- Optimized C-based backend  
- Vectorized operations  

That is why it is much faster than Python loops.

---

# 🎯 Interview Questions

- Why is Pandas built on NumPy?
- Difference between Series and DataFrame?
- Why is Pandas used in ML?
- Can DataFrame store mixed data types?
- Is Pandas faster than NumPy?

---

# 🚀 Summary

| Concept | Meaning |
|----------|----------|
| Pandas | Data analysis library |
| Series | 1D labeled array |
| DataFrame | 2D table |
| Built On | NumPy |
| Used For | ML data preprocessing |

---

# 🔜 Next Topic

- Creating DataFrame from CSV  
- Data Inspection Methods  
- Indexing & Selection  
- Handling Missing Values  
- EDA with charts  

---

# 🐼 Pandas Data Structures (AI/ML Foundation Level)

Pandas has **two main data structures**:

1️⃣ **Series** → 1D labeled data  
2️⃣ **DataFrame** → 2D labeled tabular data  

> ⚡ Everything in ML preprocessing is built on these two.

---

# 🟢 1️⃣ Creating Series

## 🔹 What is a Series?

A **Series** is:

> One-dimensional labeled array capable of holding any data type.

Think of it as:

- One column in Excel  
- One feature in ML dataset  
- Dictionary + Array hybrid  

---

## 🔹 Syntax

```python
pd.Series(data, index=None, dtype=None)
```

---

## 🔹 Creating Series from List

```python
import pandas as pd

marks = pd.Series([90, 85, 88, 92])
print(marks)
```

### ✅ Output

```
0    90
1    85
2    88
3    92
dtype: int64
```

### 🔍 Explanation

- Left side → Index  
- Right side → Values  
- `dtype` → Data type  

---

## 🔹 Custom Index

```python
marks = pd.Series([90, 85, 88], index=["Math", "Physics", "Chemistry"])
print(marks)
```

### Output

```
Math        90
Physics     85
Chemistry   88
dtype: int64
```

Now it behaves like a dictionary.

---

## 🔹 Creating Series from Dictionary

```python
data = {"Math": 90, "Physics": 85, "Chemistry": 88}

marks = pd.Series(data)
print(marks)
```

### Output

```
Math        90
Physics     85
Chemistry   88
dtype: int64
```

👉 Keys automatically become index.

---

## 🔹 Creating Series from NumPy Array

```python
import numpy as np
import pandas as pd

arr = np.array([10, 20, 30])

series = pd.Series(arr)
print(series)
```

### Output

```
0    10
1    20
2    30
dtype: int64
```

---

## 🔥 Internally

```
Series
   |
   |-- Index
   |-- Values (NumPy Array)
```

> Series = Index + NumPy Array

---

# 🟢 2️⃣ Creating DataFrame

## 🔹 What is a DataFrame?

A **DataFrame** is:

> 2-dimensional labeled data structure.

Think of it as:

- Excel Sheet  
- SQL Table  
- ML Dataset  

---

## 🔹 Syntax

```python
pd.DataFrame(data)
```

---

## 🔹 Creating DataFrame from List

### Case 1: List of Lists

```python
import pandas as pd

data = [
    ["Aman", 22, 88],
    ["Riya", 21, 92],
    ["John", 23, 85]
]

df = pd.DataFrame(data, columns=["Name", "Age", "Score"])
print(df)
```

### Output

```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
```

---

### Case 2: List of Dictionaries

```python
data = [
    {"Name": "Aman", "Age": 22},
    {"Name": "Riya", "Age": 21}
]

df = pd.DataFrame(data)
print(df)
```

---

## 🔹 Creating DataFrame from Dictionary (Most Common in ML)

```python
data = {
    "Name": ["Aman", "Riya", "John"],
    "Age": [22, 21, 23],
    "Score": [88, 92, 85]
}

df = pd.DataFrame(data)
print(df)
```

👉 Keys become column names.

---

## 🔹 Creating DataFrame from NumPy Array

```python
import numpy as np
import pandas as pd

arr = np.array([
    [22, 25000],
    [35, 60000],
    [29, 45000]
])

df = pd.DataFrame(arr, columns=["Age", "Salary"])
print(df)
```

---

## 🔹 Creating DataFrame from CSV File (🔥 Very Important in ML)

```python
df = pd.read_csv("data.csv")
print(df)
```

### Example CSV (`data.csv`)

```
Name,Age,Score
Aman,22,88
Riya,21,92
John,23,85
```

---

## 🔥 Real ML Workflow

```
CSV File
   ↓
pd.read_csv()
   ↓
DataFrame
   ↓
Cleaning
   ↓
Feature Engineering
   ↓
Model Training
```

---

# 🟢 Data Types in Pandas

| Type | Meaning |
|------|----------|
| int64 | Integer |
| float64 | Decimal |
| object | String |
| bool | True/False |
| datetime64 | Date |
| category | Categorical |

---

## 🔹 Check Data Types

```python
print(df.dtypes)
```

Example Output:

```
Name     object
Age       int64
Score     int64
dtype: object
```

---

## 🔥 Why Data Types Important in ML?

- Models need numeric input  
- Strings must be encoded  
- Dates must be converted  
- Category saves memory  

---

## 🔹 Change Data Type

```python
df["Age"] = df["Age"].astype(float)
```

---

# 🟢 Index and Columns

## 🔹 What is Index?

Index = Row labels.

Default:

```
0, 1, 2, 3 ...
```

Custom:

```python
df.index = ["A", "B", "C"]
print(df)
```

---

## 🔹 What are Columns?

Column labels:

```python
print(df.columns)
```

Output:

```
Index(['Name', 'Age', 'Score'], dtype='object')
```

---

## 🔹 Visual Diagram

```
            Columns
              ↓
        Name   Age   Score
Index  ---------------------
  0     Aman   22    88
  1     Riya   21    92
  2     John   23    85
```

- Index → Left side  
- Columns → Top  

---

# 🔥 Important ML Insight

If dataset:

```
Age   Salary   Bought
```

Then:

```python
X = df[["Age", "Salary"]]   # Features
y = df["Bought"]            # Target
```

- `X` → DataFrame  
- `y` → Series  

---

# 🧠 Internal Structure

```
DataFrame
   |
   |-- Series (Name)
   |-- Series (Age)
   |-- Series (Score)
```

> DataFrame = Collection of Series

---

# 🎯 Interview Questions

- Difference between Series and DataFrame?
- What happens if column lengths mismatch?
- Why object dtype is dangerous in ML?
- How Pandas stores data internally?
- Difference between list of dict vs dict of list?

---

# 🚀 Summary

| Concept | Key Point |
|----------|------------|
| Series | 1D labeled |
| DataFrame | 2D table |
| CSV | Real ML input |
| Index | Row labels |
| Columns | Feature names |
| dtype | Very important in ML |

---

# 🔥 Next Level (Very Important)

After creating dataset → first step in ML is:

- `.head()`
- `.tail()`
- `.info()`
- `.describe()`
- `.shape`
- `.value_counts()`

👉 Because first rule of ML:

**Always inspect your data before touching the model.**


Excellent Tapu 🚀
Now we move to Data Inspection in Pandas — this is the FIRST thing you do after loading any dataset in AI/ML.

In real ML workflow:

Load Data → Inspect Data → Clean Data → Feature Engineering → Model

Today we master the Inspect Data part deeply.

📊 We Will Use a Sample ML Dataset

Let’s create a realistic dataset:

import pandas as pd

data = {
"Name": ["Aman", "Riya", "John", "Priya", "Karan", "Rohit", "Anita"],
"Age": [22, 21, 23, 24, 22, 25, 21],
"Salary": [25000, 27000, 30000, 32000, 25000, 35000, 27000],
"Department": ["IT", "HR", "IT", "Finance", "IT", "Finance", "HR"],
"Experience": [1, 2, 2, 3, 1, 4, 2]
}

df = pd.DataFrame(data)
1️⃣ .head()
🔹 Purpose

Shows first 5 rows by default.

df.head()
✅ Output
Name  Age  Salary Department  Experience
0   Aman   22   25000         IT           1
1   Riya   21   27000         HR           2
2   John   23   30000         IT           2
3  Priya   24   32000    Finance           3
4  Karan   22   25000         IT           1
🔹 Custom Rows
df.head(3)
🔥 Why Important in ML?

Quick preview

Detect wrong columns

Detect wrong delimiter

Detect missing values visually

2️⃣ .tail()

Shows last 5 rows.

df.tail()
Output
Name  Age  Salary Department  Experience
2   John   23   30000         IT           2
3  Priya   24   32000    Finance           3
4  Karan   22   25000         IT           1
5  Rohit   25   35000    Finance           4
6  Anita   21   27000         HR           2
🔥 Why Important?

Sometimes dataset sorted by date → last rows contain latest records.

3️⃣ .info()

This is VERY IMPORTANT for ML.

df.info()
Output
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 7 entries, 0 to 6
Data columns (total 5 columns):

Column       Non-Null Count  Dtype


---

0   Name         7 non-null      object
1   Age          7 non-null      int64
2   Salary       7 non-null      int64
3   Department   7 non-null      object
4   Experience   7 non-null      int64
🔥 What It Tells You
Info	Meaning
Total rows	7
Columns	5
Missing values	Check non-null
Data types	int, object
🔥 Why Critical in ML?

Models cannot handle object type directly

Missing values must be handled

Memory usage awareness

4️⃣ .describe()

Shows statistical summary of numeric columns.

df.describe()
Output
Age        Salary   Experience
count   7.000000      7.000000     7.000000
mean   22.571429  28714.285714     2.142857
std     1.511858   3686.122312     1.069045
min    21.000000  25000.000000     1.000000
25%    21.500000  26000.000000     1.500000
50%    22.000000  27000.000000     2.000000
75%    23.500000  31000.000000     2.500000
max    25.000000  35000.000000     4.000000
🔥 Important ML Use

Detect outliers

Check skewness

Feature scaling decision

Compare min/max

🔹 Include categorical summary
df.describe(include='object')
5️⃣ .shape

Gives dataset dimensions.

df.shape

Output:

(7, 5)

Meaning:

7 rows

5 columns

🔥 ML Use
rows, cols = df.shape

Helps understand dataset size.

6️⃣ .columns

Returns column names.

df.columns

Output:

Index(['Name', 'Age', 'Salary', 'Department', 'Experience'], dtype='object')
Convert to list
list(df.columns)
7️⃣ .dtypes

Shows data type of each column.

df.dtypes

Output:

Name          object
Age            int64
Salary         int64
Department    object
Experience     int64
dtype: object
🔥 Important for ML

If you see:

object → need encoding

datetime → need conversion

category → memory optimized

8️⃣ .value_counts()

Counts frequency of unique values.

Example:

df["Department"].value_counts()

Output:

IT         3
HR         2
Finance    2
🔥 ML Use

Class imbalance detection

Feature distribution check

Example:

df["Age"].value_counts()
9️⃣ .unique()

Returns unique values.

df["Department"].unique()

Output:

array(['IT', 'HR', 'Finance'], dtype=object)
🔥 ML Use

Find categories

Prepare encoding

Detect spelling mistakes

🔥 Visual Understanding Diagram
Dataset Inspection Flow

df.head()     → Preview
df.info()     → Structure + Missing
df.describe() → Statistics
df.shape      → Size
df.dtypes     → Data types
df.value_counts() → Distribution
df.unique()   → Categories
🔥 Real ML Interview Question

If interviewer gives dataset:

First thing you do?

Answer:

df.head()
df.info()
df.describe()

Explain why.

🔥 Common Beginner Mistakes

❌ Ignoring object dtype
❌ Not checking missing values
❌ Ignoring class imbalance
❌ Not checking dataset size

🚀 Summary Table
Method	Purpose
head()	First rows
tail()	Last rows
info()	Structure
describe()	Statistics
shape	Size
columns	Column names
dtypes	Data types
value_counts()	Frequency
unique()	Unique values
🔥 Next Level (Very Important)

Now we move to:

👉 Data Selection & Filtering

Selecting columns

Selecting rows

loc

iloc

Boolean indexing

Provide such way like eariler    mean last output like
