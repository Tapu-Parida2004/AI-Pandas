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


> Excellent Tapu 🚀
> Now we move to Data Inspection in Pandas — this is the FIRST thing you do after loading any dataset in AI/ML.

> In real ML workflow:

> Load Data → Inspect Data → Clean Data → Feature Engineering → Model

> Today we master the Inspect Data part deeply.

# 📊 We Will Use a Sample ML Dataset

> Let’s create a realistic dataset:
```
import pandas as pd
```
---
```
data = {
"Name": ["Aman", "Riya", "John", "Priya", "Karan", "Rohit", "Anita"],
"Age": [22, 21, 23, 24, 22, 25, 21],
"Salary": [25000, 27000, 30000, 32000, 25000, 35000, 27000],
"Department": ["IT", "HR", "IT", "Finance", "IT", "Finance", "HR"],
"Experience": [1, 2, 2, 3, 1, 4, 2]
}
```
---
```
df = pd.DataFrame(data)
```
## 1️⃣ .head()
🔹 Purpose

> Shows first 5 rows by default.
```
df.head()
```
✅ Output
```
Name  Age  Salary Department  Experience
0   Aman   22   25000         IT           1
1   Riya   21   27000         HR           2
2   John   23   30000         IT           2
3  Priya   24   32000    Finance           3
4  Karan   22   25000         IT           1
```
🔹 Custom Rows
```
df.head(3)
```
## 🔥 Why Important in ML?

- Quick preview

- Detect wrong columns

- Detect wrong delimiter

- Detect missing values visually

## 2️⃣ .tail()

> Shows last 5 rows.
```
df.tail()
```
Output
```
Name  Age  Salary Department  Experience
2   John   23   30000         IT           2
3  Priya   24   32000    Finance           3
4  Karan   22   25000         IT           1
5  Rohit   25   35000    Finance           4
6  Anita   21   27000         HR           2
```
## 🔥 Why Important?

> Sometimes dataset sorted by date → last rows contain latest records.

## 3️⃣ .info()

> This is VERY IMPORTANT for ML.

df.info()
## Output
> <class 'pandas.core.frame.DataFrame'>
> RangeIndex: 7 entries, 0 to 6
> Data columns (total 5 columns):
```
Column       Non-Null Count  Dtype
0   Name         7 non-null      object
1   Age          7 non-null      int64
2   Salary       7 non-null      int64
3   Department   7 non-null      object
4   Experience   7 non-null      int64
```

## 🔥 What It Tells You
Info	Meaning
Total rows	7
Columns	5
Missing values	Check non-null
Data types	int, object
## 🔥 Why Critical in ML?

- Models cannot handle object type directly

- Missing values must be handled

- Memory usage awareness

# 4️⃣ .describe()

Shows statistical summary of numeric columns.

df.describe()
## Output
```
Age        Salary   Experience
count   7.000000      7.000000     7.000000
mean   22.571429  28714.285714     2.142857
std     1.511858   3686.122312     1.069045
min    21.000000  25000.000000     1.000000
25%    21.500000  26000.000000     1.500000
50%    22.000000  27000.000000     2.000000
75%    23.500000  31000.000000     2.500000
max    25.000000  35000.000000     4.000000
```
## 🔥 Important ML Use

- Detect outliers

- Check skewness

- Feature scaling decision

- Compare min/max

## 🔹 Include categorical summary
df.describe(include='object')
# 5️⃣ .shape

Gives dataset dimensions.

df.shape

## Output:
```
(7, 5)
```
Meaning:
```
7 rows

5 columns
```
## 🔥 ML Use
```
rows, cols = df.shape
```
Helps understand dataset size.

# 6️⃣ .columns

Returns column names.

df.columns

## Output:
```
Index(['Name', 'Age', 'Salary', 'Department', 'Experience'], dtype='object')
```
Convert to list
```
list(df.columns)
```
# 7️⃣ .dtypes

Shows data type of each column.
```
df.dtypes
```
## Output:
```
Name          object
Age            int64
Salary         int64
Department    object
Experience     int64
dtype: object
```
## 🔥 Important for ML

If you see:
```
object → need encoding

datetime → need conversion

category → memory optimized
```
## 8️⃣ .value_counts()

Counts frequency of unique values.

## Example:
```
df["Department"].value_counts()
```
## Output:
```
IT         3
HR         2
Finance    2
```
## 🔥 ML Use

- Class imbalance detection

- Feature distribution check

## Example:
```
df["Age"].value_counts()
```
## 9️⃣ .unique()

Returns unique values.
```
df["Department"].unique()
```
## Output:
```
array(['IT', 'HR', 'Finance'], dtype=object)
```
## 🔥 ML Use

- Find categories

- Prepare encoding

- Detect spelling mistakes

## 🔥 Visual Understanding Diagram
Dataset Inspection Flow
```
df.head()     → Preview
df.info()     → Structure + Missing
df.describe() → Statistics
df.shape      → Size
df.dtypes     → Data types
df.value_counts() → Distribution
df.unique()   → Categories
```
## 🔥 Real ML Interview Question

If interviewer gives dataset:

First thing you do?

Answer:
```
df.head()
df.info()
df.describe()
```
Explain why.

## 🔥 Common Beginner Mistakes

- ❌ Ignoring object dtype
- ❌ Not checking missing values
- ❌ Ignoring class imbalance
- ❌ Not checking dataset size

## 🚀 Summary Table
```
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
```
## 🔥 Next Level (Very Important)

Now we move to:

## 👉 Data Selection & Filtering

- Selecting columns

- Selecting rows

- loc

- iloc

- Boolean indexing

# 🔍 Pandas Data Inspection (First Step in ML)

After loading a dataset, the **first thing every Data Scientist does is inspect the data.**

This helps to understand:

- Dataset size
- Column names
- Data types
- Missing values
- Data distribution

📌 These functions are used in **almost every ML project**.

---

# 🟢 1️⃣ `.head()`

## 🔹 Purpose

Displays the **first 5 rows** of the dataset.

Useful for quickly checking whether the dataset loaded correctly.

---

## 🔹 Syntax

```python
df.head()
```

---

## 🔹 Example

```python
import pandas as pd

df = pd.read_csv("data.csv")

print(df.head())
```

### Output

```
   Name   Age   Salary
0  Aman   22   25000
1  Riya   21   30000
2  John   23   28000
3  Sara   24   35000
4  Alex   22   27000
```

---

## 🔹 Show Custom Rows

```python
df.head(3)
```

Output:

```
   Name   Age   Salary
0  Aman   22   25000
1  Riya   21   30000
2  John   23   28000
```

---

# 🟢 2️⃣ `.tail()`

## 🔹 Purpose

Displays the **last 5 rows** of the dataset.

Very useful when datasets are large.

---

## 🔹 Syntax

```python
df.tail()
```

---

## 🔹 Example

```python
print(df.tail())
```

### Output

```
    Name   Age   Salary
95  Sam    26   45000
96  Nina   29   52000
97  Rahul  30   55000
98  Ankit  27   47000
99  Pooja  28   49000
```

---

# 🟢 3️⃣ `.info()`

## 🔹 Purpose

Shows **complete summary of dataset**.

Includes:

- Column names
- Data types
- Non-null values
- Memory usage

---

## 🔹 Syntax

```python
df.info()
```

---

## 🔹 Example Output

```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 100 entries, 0 to 99
Data columns (total 3 columns):

Column     Non-Null Count   Dtype
---------------------------------
Name       100 non-null     object
Age        100 non-null     int64
Salary     98 non-null      float64

memory usage: 2.5 KB
```

---

## 🔥 Why `.info()` Important in ML?

It helps detect:

- Missing values
- Wrong data types
- Dataset size

---

# 🟢 4️⃣ `.describe()`

## 🔹 Purpose

Shows **statistical summary of numeric columns**.

---

## 🔹 Syntax

```python
df.describe()
```

---

## 🔹 Example Output

```
            Age      Salary
count      100        100
mean       25.3     35000
std        3.5       5000
min        21       25000
25%        23       30000
50%        25       34000
75%        27       40000
max        32       55000
```

---

## 🔹 Explanation

| Metric | Meaning |
|------|------|
| count | Number of values |
| mean | Average |
| std | Standard deviation |
| min | Minimum value |
| max | Maximum value |
| 25% | First quartile |
| 50% | Median |
| 75% | Third quartile |

---

# 🟢 5️⃣ `.shape`

## 🔹 Purpose

Shows **dataset dimensions**.

---

## 🔹 Syntax

```python
df.shape
```

---

## 🔹 Example Output

```
(100, 3)
```

Meaning:

```
Rows = 100
Columns = 3
```

---

# 🟢 6️⃣ `.columns`

## 🔹 Purpose

Shows **all column names**.

---

## 🔹 Syntax

```python
df.columns
```

---

## 🔹 Example Output

```
Index(['Name', 'Age', 'Salary'], dtype='object')
```

---

## 🔹 Convert to List

```python
list(df.columns)
```

Output:

```
['Name', 'Age', 'Salary']
```

---

# 🟢 7️⃣ `.dtypes`

## 🔹 Purpose

Shows **data types of all columns**.

---

## 🔹 Syntax

```python
df.dtypes
```

---

## 🔹 Example Output

```
Name       object
Age        int64
Salary     float64
dtype: object
```

---

## 🔥 Important for ML

Machine learning models need **numeric data**.

So:

- Strings → Encoding
- Dates → Feature extraction
- Categories → Label encoding

---

# 🟢 8️⃣ `.value_counts()`

## 🔹 Purpose

Counts frequency of unique values.

Useful for **categorical data analysis**.

---

## 🔹 Syntax

```python
df["column"].value_counts()
```

---

## 🔹 Example

```python
df["Gender"].value_counts()
```

### Output

```
Male      60
Female    40
```

---

# 🟢 9️⃣ `.unique()`

## 🔹 Purpose

Returns **unique values** in a column.

---

## 🔹 Syntax

```python
df["column"].unique()
```

---

## 🔹 Example

```python
df["City"].unique()
```

### Output

```
['Delhi', 'Mumbai', 'Bangalore']
```

---

# 🔥 Typical ML Workflow

```
Load Dataset
     ↓
df.head()
     ↓
df.info()
     ↓
df.describe()
     ↓
df.dtypes
     ↓
df.value_counts()
```

This step is called:

# 📊 Data Inspection / Exploratory Analysis

---

# 🎯 Interview Questions

1️⃣ Difference between `head()` and `tail()`  
2️⃣ Why `.info()` is used in ML preprocessing?  
3️⃣ Difference between `.unique()` and `.value_counts()`  
4️⃣ What does `.describe()` return?  
5️⃣ What does `(100, 5)` mean in `.shape`?

---

# 🚀 Summary

| Function | Purpose |
|------|------|
| head() | First rows |
| tail() | Last rows |
| info() | Dataset summary |
| describe() | Statistical summary |
| shape | Dataset size |
| columns | Column names |
| dtypes | Data types |
| value_counts() | Frequency |
| unique() | Unique values |

✅ Now your GitHub README will look like a professional Data Science notebook.

If you want, I can also show you something very powerful for your GitHub learning system:

How to structure your entire AI/ML notes repository like a professional engineer

Example:

AI-ML-NOTES
│
├── 01_Python
├── 02_NumPy
├── 03_Pandas
│      ├── Data_Structures.md
│      ├── Data_Inspection.md
│      ├── Data_Cleaning.md
│
├── 04_Data_Visualization
├── 05_Machine_Learning


📁 AI / ML Learning Repository Structure

Create a GitHub repository like this:
```
AI-ML-NOTES
│
├── README.md
│
├── 01_Python
│   ├── basics.md
│   ├── functions.md
│   ├── OOP.md
│
├── 02_NumPy
│   ├── numpy_basics.md
│   ├── array_operations.md
│   ├── broadcasting.md
│
├── 03_Pandas
│   ├── introduction.md
│   ├── data_structures.md
│   ├── data_inspection.md
│   ├── data_cleaning.md
│   ├── groupby.md
│   ├── merging_joining.md
│   ├── time_series.md
│
├── 04_Data_Visualization
│   ├── matplotlib.md
│   ├── seaborn.md
│
├── 05_Machine_Learning
│   ├── ML_basics.md
│   ├── supervised_learning.md
│   ├── unsupervised_learning.md
│
├── 06_Projects
│   ├── titanic_project.md
│   ├── house_price_prediction.md
│   ├── sales_forecasting.md
🧾 Main README.md (Homepage)
```
Put this in your main README.md so your repo looks professional.

Writing
🤖 AI & Machine Learning Learning Notes

This repository contains my structured learning notes for becoming a Machine Learning Engineer / AI Engineer.

It covers:

Python for Data Science

NumPy

Pandas

Data Visualization

Machine Learning

Real-world Projects

📚 Learning Roadmap
🐍 Python

Basics

Functions

Object Oriented Programming

🔢 NumPy

Arrays

Vectorization

Broadcasting

🐼 Pandas

Data Structures

Data Inspection

Data Cleaning

GroupBy

Merging & Joining

Time Series Analysis

📊 Data Visualization

Matplotlib

Seaborn

🤖 Machine Learning

Supervised Learning

Unsupervised Learning

Feature Engineering

Model Evaluation

🚀 Projects

Titanic Survival Prediction

House Price Prediction

Sales Forecasting

🛠 Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

🎯 Goal

To master AI / Machine Learning and build real-world projects.

⭐ If this repository helps you, feel free to star it!

📄 Example: Pandas Folder

Inside 03_Pandas, create files like:

03_Pandas
│
├── introduction.md
├── data_structures.md
├── data_inspection.md
├── missing_values.md
├── groupby.md
├── merging_joining.md
🧠 Example Internal Markdown (clean notes)

Example data_inspection.md

# Pandas Data Inspection

## head()

Shows first rows.

```python
df.head()
info()

Shows dataset information.

df.info()
describe()

Statistical summary.

df.describe()

---

# 💻 How to Create This in 3 Minutes

### Step 1
Go to **GitHub**

Click:


New Repository


Name:


AI-ML-NOTES


---

### Step 2

Create folders locally:


mkdir AI-ML-NOTES
cd AI-ML-NOTES
mkdir 01_Python
mkdir 02_NumPy
mkdir 03_Pandas
mkdir 04_Data_Visualization
mkdir 05_Machine_Learning
mkdir 06_Projects


---

### Step 3

Push to GitHub


git init
git add .
git commit -m "Initial AI ML Notes"
git branch -M main
git remote add origin YOUR_REPO_LINK
git push -u origin main


---

# 📈 Why This Is Powerful (for Jobs)

When recruiters open your GitHub they see:


Clean Notes
Structured Learning
Real ML Projects


This shows:

✔ Consistency  
✔ Knowledge  
✔ Professional learning

---

# 🚀 Next Level (Very Powerful)

If you want, I can also show you:

### 🔥 **How to make your GitHub notes look like a professional documentation website**

Example like:


https://pandas.pydata.org/docs/


Using:

- GitHub Pages
- Markdown
- Auto navigation

You can open it in office like a **personal ML textbook**. 📚
4️⃣ Selecting Data

Selecting columns

Selecting multiple columns

Row selection

.loc[]

.iloc[]    GitHub README template that makes your notes look like a professional documentation site.

Below is a clean GitHub README.md style documentation section you can paste directly into your repo.
It is structured like professional documentation (similar to official docs) with sections, tables, code blocks, diagrams, and outputs.

🐼 Pandas – Selecting Data

Data selection is one of the most frequently used operations in data analysis and machine learning preprocessing.

In real ML workflows, you constantly need to:

Select specific features (columns)

Select specific records (rows)

Extract training variables

Filter subsets of data

Pandas provides several powerful ways to select data.

📚 Topics Covered

Selecting Columns

Selecting Multiple Columns

Row Selection

.loc[] – Label Based Selection

.iloc[] – Position Based Selection

## 1️⃣ Selecting Columns

Selecting a column returns a Series.

## Syntax
```
df["column_name"]
```
## Example
```
import pandas as pd

data = {
    "Name": ["Aman", "Riya", "John"],
    "Age": [22, 21, 23],
    "Score": [88, 92, 85]
}

df = pd.DataFrame(data)

print(df["Name"])
```
## Output
```
0    Aman
1    Riya
2    John
Name: Name, dtype: object
```
## Explanation
Component	Meaning
0,1,2	Index
Aman,Riya,John	Values
dtype	Data type
Important

Selecting one column returns:

Series
## 2️⃣ Selecting Multiple Columns

Selecting multiple columns returns a DataFrame.

Syntax
df[["col1", "col2"]]
Example
print(df[["Name", "Score"]])
Output
   Name  Score
0  Aman     88
1  Riya     92
2  John     85
Important Rule

Single bracket:
```
df["Name"] → Series
```
Double bracket:
```
df[["Name"]] → DataFrame
```
## 3️⃣ Row Selection

Rows can be selected using index position.

Example
```
print(df[0:2])
```
Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
```
Explanation
```
0:2
```
Means:
```
Start → index 0
End → index 2 (excluded)
```
## 4️⃣ .loc[] – Label Based Selection

.loc[] selects data using row labels and column names.

## Syntax
```
df.loc[row_label, column_label]
```
Example 1: Select Row
```
print(df.loc[1])
```
## Output
``
Name     Riya
Age        21
Score      92
Name: 1, dtype: object
Example 2: Select Row + Column
print(df.loc[1, "Name"])
``
## Output
```
Riya
Example 3: Multiple Rows
print(df.loc[0:1])
```
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
```
## 5️⃣ .iloc[] – Position Based Selection

.iloc[] selects data based on integer position.

## Syntax
```
df.iloc[row_position, column_position]
Example 1: Select Row
print(df.iloc[1])
```
## Output
```
Name     Riya
Age        21
Score      92
Name: 1, dtype: object
```
## Example 2: Select Specific Value
```
print(df.iloc[1,0])
```
Output
```
Riya
```
## Example 3: Select Multiple Rows
```
print(df.iloc[0:2])
```
Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
```
## 🧠 .loc[] vs .iloc[]
Feature	.loc[]	.iloc[]
Selection Type	Label based	Position based
Index Type	Row/Column names	Integer index
Inclusive Range	Yes	No
Usage	Named data	Numerical position
## 📊 Visual Explanation

## Dataset:
```
Index   Name   Age   Score
0       Aman   22    88
1       Riya   21    92
2       John   23    85
```
## Examples:
```
df.loc[1]
```
Returns
```
Riya row
```
```
df.iloc[1]
```
Returns

Row at position 1
## 🤖 Machine Learning Example

Typical ML dataset:
```
Age   Salary   Purchased
22    25000       0
35    60000       1
````
Selecting features (X):
```
X = df[["Age", "Salary"]]
```
Selecting target variable (y):

y = df["Purchased"]
X → DataFrame
y → Series
⚠️ Common Mistakes
Mistake 1
```
df["Name","Age"]
```
## ❌ Wrong

Correct:
```
df[["Name","Age"]]
```
Mistake 2

Confusing .loc and .iloc
```
.loc → label
.iloc → position
```
## 🎯 Interview Questions

1️⃣ Difference between .loc[] and .iloc[]
2️⃣ Why does selecting one column return a Series?
3️⃣ How do you select multiple columns in Pandas?
4️⃣ How do you extract features and target variable?

## 🚀 Next Topic

Next documentation section:
```
Boolean Indexing
Conditional Filtering
Query Method
```
These are very important for real-world data filtering in ML projects.

If you want, I can also give you a 🔥 professional GitHub README UI template used by top AI engineers, which includes:

- Navigation menu

- Collapsible sections

- Clean badges

- Quick links

Table of contents

Your repo will look like official documentation.
```
Boolean Indexing
Conditional Filtering
Query Method
```
Below is a professional GitHub README.md documentation-style note you can paste directly into your repo.
It follows the same structured style as previous sections so your Pandas notes look like a real documentation site.

## 🐼 Pandas – Boolean Indexing & Conditional Filtering

Boolean indexing is one of the most powerful features of Pandas.
It allows you to filter rows based on conditions, which is extremely common in data cleaning and ML preprocessing.

In real-world machine learning workflows, you often need to:

Filter data based on conditions

Remove unwanted records

Select rows that match criteria

Create subsets of datasets

## 📚 Topics Covered

- Boolean Indexing

- Conditional Filtering

- Query Method

## 1️⃣ Boolean Indexing

Boolean indexing means selecting rows using True / False conditions.

When a condition is applied, Pandas creates a Boolean mask.
```
True  → Row selected
False → Row ignored
```
Example Dataset
```
import pandas as pd

data = {
    "Name": ["Aman", "Riya", "John", "Sara"],
    "Age": [22, 21, 23, 20],
    "Score": [88, 92, 85, 70]
}

df = pd.DataFrame(data)

print(df)
```
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
3  Sara   20     70
```
## Example: Boolean Condition
```
df["Score"] > 85
```
## Output
```
0     True
1     True
2    False
3    False
Name: Score, dtype: bool
```
Explanation:
```
Index	Score	Condition (>85)

0	88	True
1	92	True
2	85	False
3	70	False
```
Filtering Using Boolean Index
```
df[df["Score"] > 85]
``
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
```
Only rows where Score > 85 are returned.

## 2️⃣ Conditional Filtering

Multiple conditions can be applied using logical operators.

Operator	Meaning
&	AND
`	`
~	NOT

## ⚠ Important: Conditions must be inside parentheses.

## Example 1 – AND Condition

Filter students with:
```
Score > 80 AND Age > 21
df[(df["Score"] > 80) & (df["Age"] > 21)]
```
## Output
```
   Name  Age  Score
0  Aman   22     88
2  John   23     85
```
## Example 2 – OR Condition
```
df[(df["Score"] > 90) | (df["Age"] < 21)]
```
## Output
```
   Name  Age  Score
1  Riya   21     92
3  Sara   20     70
```
## Example 3 – NOT Condition
```
df[~(df["Score"] > 85)]
```
Output
```
   Name  Age  Score
2  John   23     85
3  Sara   20     70
```
Visual Explanation

Original Dataset
```
Index   Name   Age   Score
0       Aman   22    88
1       Riya   21    92
2       John   23    85
3       Sara   20    70
```
Condition:
```
Score > 85
```
Boolean Mask
```
[True, True, False, False]
```
## Filtered Result
```
Aman
Riya
```
## 3️⃣ Query Method

Pandas provides a clean SQL-like syntax for filtering using .query().

This is often used in large datasets and production pipelines.

## Syntax
```
df.query("condition")
```
## Example
df.query("Score > 85")
Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
```
Multiple Conditions
```
df.query("Score > 80 and Age > 21")
```
Output
```
   Name  Age  Score
0  Aman   22     88
2  John   23     85
```
Query vs Boolean Indexing
Method	Example	Style
Boolean Indexing	df[df["Score"] > 85]	Pythonic
Query	df.query("Score > 85")	SQL-like

Both give the same result.

## 🤖 Machine Learning Example

Imagine dataset:
```
Age   Salary   Purchased
22    25000       0
35    60000       1
29    45000       1
```
Filtering high salary customers:
```
df[df["Salary"] > 40000]
```
## Output
```
Age   Salary   Purchased
35    60000       1
29    45000       1
```
This helps in:

Customer segmentation

Fraud detection

Feature engineering

## ⚠️ Common Mistakes
Missing parentheses

## ❌ Wrong
```
df[df["Age"] > 20 & df["Score"] > 80]
```
## ✔ Correct
```
df[(df["Age"] > 20) & (df["Score"] > 80)]
```
## 🎯 Interview Questions

1️⃣ What is Boolean indexing in Pandas?
2️⃣ Difference between & and and in Pandas?
3️⃣ Why are parentheses required in conditions?
4️⃣ Difference between .query() and Boolean indexing?

🚀 Next Topic

Next documentation section:

Indexing & Reindexing

Topics include:

Setting Index

Resetting Index

Multi Index

sort_values()

sort_index()

These are very important for real ML dataset manipulation.

## 5️⃣ Indexing & Reindexing

- Setting index

- Resetting index
 
- Multi-index

Sorting:

- sort_values()

- sort_index()

Below is a clean professional GitHub README.md documentation section for your Pandas notes.
You can paste this directly into your repository (for example 03_Pandas/indexing_reindexing.md).
It follows documentation style like official libraries with tables, code, outputs, diagrams, and explanations.

## 🐼 Pandas – Indexing & Reindexing

Indexing is a core concept in Pandas.
Every row in a DataFrame has an index (label) that helps identify and access data efficiently.

In real-world Machine Learning workflows, indexing is used for:

Identifying records

Setting meaningful row labels

Working with hierarchical datasets

Sorting and organizing data

## 📚 Topics Covered
```
Setting Index

Resetting Index

Multi-Index (Hierarchical Index)

Sorting Data

sort_values()

sort_index()
```
## 1️⃣ Setting Index

The index represents the row labels of a DataFrame.

By default, Pandas assigns an integer index.

Default Index
```
import pandas as pd

data = {
    "Name": ["Aman", "Riya", "John"],
    "Age": [22, 21, 23],
    "Score": [88, 92, 85]
}

df = pd.DataFrame(data)

print(df)
```
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
```
Here:

0,1,2 = Default Index
Setting a Column as Index

Sometimes we want a meaningful identifier as the index.

Example: Student ID or Name.

## Syntax
```
df.set_index("column_name")
```
## Example
```
df = df.set_index("Name")
print(df)
```
### Output
```
      Age  Score
Name
Aman   22     88
Riya   21     92
John   23     85
```
Now the Name column becomes the index.

Permanent Change
```
df.set_index("Name", inplace=True)
```
inplace=True modifies the original DataFrame.

## 2️⃣ Resetting Index

Resetting index converts the index back to a column.

Syntax
```
df.reset_index()
```
## Example
```
df = df.reset_index()

print(df)
```
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
```
Reset Without Adding Old Index
```
df.reset_index(drop=True)
```
This removes the previous index completely.

## 3️⃣ Multi-Index (Hierarchical Index)

A Multi-Index allows multiple columns to act as the index.

This is useful for hierarchical datasets.

Example:
```
Country → City → Population
```
Example Dataset
```
data = {
    "Country": ["India", "India", "USA", "USA"],
    "City": ["Mumbai", "Delhi", "NY", "LA"],
    "Population": [20, 18, 8, 4]
}

df = pd.DataFrame(data)
Creating Multi-Index
df = df.set_index(["Country", "City"])

print(df)
```
## Output
```
               Population
Country City
India   Mumbai        20
        Delhi         18
USA     NY             8
        LA             4
        ```
Diagram
```
Country
   └── City
        └── Population
```
Multi-index allows hierarchical data analysis.

## 4️⃣ Sorting Data

Sorting helps organize datasets based on values or index.

Pandas provides two main sorting methods:
```
Method	Purpose
sort_values()	Sort by column values
sort_index()	Sort by index
sort_values()
```
Sorts rows based on column values.

Syntax
```
df.sort_values(by="column_name")
```
## Example
```
df.sort_values(by="Score")
```
## Output
```
   Name  Age  Score
2  John   23     85
0  Aman   22     88
1  Riya   21     92
```
Sorted by Score ascending.

Descending Order
```
df.sort_values(by="Score", ascending=False)
```
Output
```
   Name  Age  Score
1  Riya   21     92
0  Aman   22     88
2  John   23     85
```
Sorting by Multiple Columns
```
df.sort_values(by=["Age", "Score"])
```
This sorts first by Age, then by Score.
```
sort_index()
```
Sorts rows based on index labels.

## Syntax
```
df.sort_index()
```
## Example
```
df.sort_index()
```
## Output
```
   Name  Age  Score
0  Aman   22     88
1  Riya   21     92
2  John   23     85
```
Descending Index
```
df.sort_index(ascending=False)
```
Visual Summary

Original Data
```
Index  Name   Age   Score
2      John   23    85
0      Aman   22    88
1      Riya   21    92
```
After sort_index()
```
0  Aman
1  Riya
2  John
```
After sort_values("Score")
```
John
Aman
Riya
```
## 🤖 Machine Learning Example

Dataset:
```
CustomerID  Age  Purchase
C101        25     1
C102        30     0
```
Setting index:
```
df.set_index("CustomerID")
```
Benefits:

Unique identifier

Easier lookups

Faster joins and merges

⚠️ Common Mistakes
Forgetting inplace
```
df.set_index("Name")
```
This does not modify original DataFrame unless:
```
inplace=True
```
Confusing sort_index() and sort_values()
Function	Sorts by
```
sort_index()	Row labels
sort_values()	Column values
```
## 🎯 Interview Questions

1️⃣ What is the difference between index and columns in Pandas?
2️⃣ When should you use Multi-Index?
3️⃣ Difference between sort_index() and sort_values()?
4️⃣ Why is indexing important in data analysis?

## 🚀 Next Topic

Next documentation section:

Handling Missing Values

Including:
```
isnull()

notnull()

dropna()

fillna()

Forward Fill

Backward Fill

Replacing Missing Values
```
This is one of the most important topics for Machine Learning preprocessing.

## 6️⃣ Handling Missing Values

- isnull()

- notnull()

- dropna()

- fillna()

- Forward fill / backward fill

- Replacing values.  all detailed elaborately

Below is a professional GitHub README.md documentation-style note you can directly paste into your repo.
It is fully structured, ML-focused, with code, outputs, tables, diagrams, and explanations so it looks like real technical documentation.

## 🐼 Pandas – Handling Missing Values

Handling missing data is one of the most important steps in Machine Learning preprocessing.

In real-world datasets:

Data may be incomplete

Sensors may fail

Users may skip fields

Data collection may have errors

Because of this, missing values appear frequently.

Example dataset:
```
Name   Age   Salary
Aman   22    25000
Riya   NaN   30000
John   25    NaN
```
Machine learning models cannot work with missing values, so we must detect and handle them properly.

## 📚 Topics Covered

What are Missing Values
```
isnull()

notnull()

dropna()

fillna()

Forward Fill / Backward Fill

Replacing Values
```
## 1️⃣ What Are Missing Values?

Missing values in Pandas are represented as:
```
NaN → Not a Number
None
NaT → Missing datetime
```
Example dataset:
```
import pandas as pd
import numpy as np

data = {
    "Name": ["Aman", "Riya", "John", "Sara"],
    "Age": [22, np.nan, 24, 21],
    "Salary": [25000, 30000, np.nan, 28000]
}

df = pd.DataFrame(data)

print(df)
```
## Output
```
   Name   Age   Salary
0  Aman  22.0  25000.0
1  Riya   NaN  30000.0
2  John  24.0      NaN
3  Sara  21.0  28000.0
```
Here:
```
NaN = Missing value
```
## 2️⃣ isnull()

isnull() is used to detect missing values.

## Syntax
``
df.isnull()
```
## Example
```
df.isnull()
```
## Output
```
    Name    Age  Salary
0  False  False   False
1  False   True   False
2  False  False    True
3  False  False   False
``
## Explanation:
```
Value	Meaning
True	Missing value
False	Value exists
Count Missing Values
df.isnull().sum()
Output
Name      0
Age       1
Salary    1
dtype: int64
```
This tells how many missing values exist in each column.

## 3️⃣ notnull()

notnull() is the opposite of isnull().

It returns:
```
True → Value exists
False → Missing value
```
## Example
```
df.notnull()
```
## Output
```
    Name   Age  Salary
0   True  True   True
1   True False   True
2   True  True  False
3   True  True   True
```
## 4️⃣ dropna()

dropna() removes rows or columns containing missing values.

Drop Rows with Missing Values
## Syntax
```
df.dropna()
```
## Example
```
df.dropna()
```
## Output
```
   Name   Age   Salary
0  Aman  22.0  25000.0
3  Sara  21.0  28000.0
```
Rows containing NaN are removed.

Drop Columns with Missing Values
```
df.dropna(axis=1)
```
## Output
```
   Name
0  Aman
1  Riya
2  John
3  Sara
```
## Explanation:
```
axis = 0 → rows
axis = 1 → columns
Drop Rows if All Values Missing
df.dropna(how="all")
Drop Rows if Any Value Missing
df.dropna(how="any")
```
## 5️⃣ fillna()

Instead of removing data, we can replace missing values.

## Syntax
```
df.fillna(value)
```
Example – Fill with Constant Value
```
df.fillna(0)
```
Output
```
   Name   Age   Salary
0  Aman  22.0  25000.0
1  Riya   0.0  30000.0
2  John  24.0      0.0
3  Sara  21.0  28000.0
```
Fill with Mean Value

Common in ML preprocessing.
```
df["Age"].fillna(df["Age"].mean(), inplace=True)
```
Example:
```
Mean Age = 22.33
```
Missing age will be replaced with 22.33.

Fill with Median

Better for outliers.
```
df["Salary"].fillna(df["Salary"].median())
```
Fill with Mode

Used for categorical variables.
```
df["City"].fillna(df["City"].mode()[0])
```
## 6️⃣ Forward Fill / Backward Fill

- These methods copy nearby values.

- Used in time-series data.

- Forward Fill (ffill)

- Fills missing values with the previous value.
```
df.fillna(method="ffill")
```
## Example:
```
Original
10
NaN
NaN
15

Forward Fill
10
10
10
15
Backward Fill (bfill)
```
Fills missing values with the next value.
```
df.fillna(method="bfill")
```
## Example:

Original
```
10
NaN
NaN
15
```
Backward Fill
```
10
15
15
15
```
Visual Explanation
Original Data
```
Index  Value
0      10
1      NaN
2      NaN
3      20
```
Forward Fill
```
10
10
10
20
```
Backward Fill
```
10
20
20
20
```
## 7️⃣ Replacing Values

Sometimes missing values are represented as:
```
"?"
"N/A"
"unknown"
"-"
```
These must be converted to NaN first.

Replace Example
```
df.replace("?", np.nan)
Replace Multiple Values
df.replace(["?", "N/A"], np.nan)
```
Replace Specific Column
```
df["Age"].replace("unknown", np.nan)
```
## 🤖 Machine Learning Best Practices

Handling missing values properly is critical in ML.

## Common strategies:

- Data Type	Strategy
- Numerical	Mean / Median
- Categorical	Mode
- Time Series	Forward Fill
- Large Missing %	Drop column
## Example ML Workflow
```
Raw Dataset
      ↓
Detect Missing Values
      ↓
isnull().sum()
      ↓
Fill Missing Values
      ↓
fillna(mean / median)
      ↓
Clean Dataset
      ↓
Train ML Model
```
## ⚠️ Common Mistakes
Dropping Too Much Data
df.dropna()
```
May remove too many rows.

Filling with Wrong Value
```
Example:
```
Filling salary with 0

This may distort model predictions.
```
## 🎯 Interview Questions
```
1️⃣ What is NaN in Pandas?
2️⃣ Difference between isnull() and notnull()?
3️⃣ When should you use dropna() vs fillna()?
4️⃣ Why is median better than mean for outliers?
5️⃣ What is forward fill?
```
## 🚀 Next Topic

Next documentation section:

Handling Duplicates

Topics include:
```
duplicated()

drop_duplicates()
```
These are also very important for cleaning real-world datasets.

If you want, I can also help you build a complete GitHub Pandas Notes Repository structure like this:
```
Pandas-For-AI-ML/
│
├── 01_Introduction
├── 02_Data_Structures
├── 03_Data_Inspection
├── 04_Data_Selection
├── 05_Indexing
├── 06_Missing_Values
├── 07_Duplicates
├── 08_Data_Types
├── 09_String_Operations
```
It will look like a professional AI engineer learning repository.

## 7️⃣ Handling Duplicates
  ```
duplicated()

drop_duplicates()
```
Below is a professional GitHub README documentation style note you can directly paste into your README.md.
It follows the same structured learning format you have been using so you can easily open it in office and revise quickly.

## 🐼 Pandas for Machine Learning — Phase 2
## 7️⃣ Handling Duplicates in Pandas

Duplicate data is very common in real-world datasets.
Duplicates can occur because of:

- Data entry errors

- Data merging mistakes

- Repeated records

- System logging duplicates

Handling duplicates is important because they can:

- Bias machine learning models

- Inflate statistics

- Distort analysis

Pandas provides two main functions:
```
duplicated()
drop_duplicates()
```
## 1️⃣ Detecting Duplicates — duplicated()

The duplicated() function checks whether a row is a duplicate of a previous row.

It returns a Boolean Series:
```
True → duplicate row

False → unique row
```
Example Dataset
```
import pandas as pd

data = {
    "Name": ["Alice", "Bob", "Alice", "David", "Bob"],
    "Age": [25, 30, 25, 40, 30],
    "City": ["NY", "LA", "NY", "Chicago", "LA"]
}

df = pd.DataFrame(data)

print(df)
```
Output:
```
    Name  Age     City
0  Alice   25       NY
1    Bob   30       LA
2  Alice   25       NY
3  David   40  Chicago
4    Bob   30       LA
```
Here rows 2 and 4 are duplicates.

Check Duplicate Rows
```
df.duplicated()
```
## Output:
```
0    False
1    False
2     True
3    False
4     True
dtype: bool
```
## Explanation:
```
Row 2 duplicates row 0

Row 4 duplicates row 1
```
Show Only Duplicate Rows
````
df[df.duplicated()]
``
Output
```
    Name  Age City
2  Alice   25   NY
4    Bob   30   LA
Mark All Duplicates
```
By default, the first occurrence is not marked as duplicate.

If you want to mark all duplicates, use:
````
df.duplicated(keep=False)
```
Output:
```
0     True
1     True
2     True
3    False
4     True
```
Now both original and duplicate rows are marked.

## 2️⃣ Detect Duplicates Based on Specific Columns

Sometimes duplicates should be checked only for certain columns.

Example:
```
df.duplicated(subset=["Name"])
```
Output
```
0    False
1    False
2     True
3    False
4     True
```
This checks duplicates only in the Name column.

## 3️⃣ Removing Duplicate Rows — drop_duplicates()

To remove duplicates permanently:
```
df.drop_duplicates()
```
Output
```
    Name  Age     City
0  Alice   25       NY
1    Bob   30       LA
3  David   40  Chicago
```
Duplicates are removed automatically.

Remove Duplicates In-place
```
df.drop_duplicates(inplace=True)
```
Now the original dataframe is updated.

## 4️⃣ Keep First or Last Duplicate
Keep First (default)
```
df.drop_duplicates(keep="first")
```
Keeps the first occurrence.

Keep Last
```
df.drop_duplicates(keep="last")
```
Output:
```
    Name  Age     City
2  Alice   25       NY
3  David   40  Chicago
4    Bob   30       LA
Remove All Duplicates
df.drop_duplicates(keep=False)
```
Output:
```
    Name  Age     City
3  David   40  Chicago
```
Only completely unique rows remain.

## 5️⃣ Remove Duplicates Based on Specific Columns

Example:
```
df.drop_duplicates(subset=["Name"])
```
Output
```
    Name  Age     City
0  Alice   25       NY
1    Bob   30       LA
3  David   40  Chicago
```
Duplicates are removed based on Name column only.

## 6️⃣ Real-World Example (Machine Learning Dataset)

Imagine a customer dataset:
```
df = pd.read_csv("customers.csv")
```
Check duplicates:
```
df[df.duplicated()]
```
Remove duplicates based on CustomerID:
```
df = df.drop_duplicates(subset=["CustomerID"])
```
This ensures each customer appears only once.

## 7️⃣ Visual Understanding

Example dataset
```
Row   Name   Age   City
-----------------------
0     Alice  25    NY
1     Bob    30    LA
2     Alice  25    NY   ← Duplicate
3     David  40    Chicago
4     Bob    30    LA   ← Duplicate
```
After removing duplicates:
```
Row   Name   Age   City
-----------------------
0     Alice  25    NY
1     Bob    30    LA
3     David  40    Chicago
```
## 8️⃣ Best Practices for ML

Always check duplicates before training a model.

Typical workflow:

# Step 1
```
df.info()
```
# Step 2
```
df.duplicated().sum()
```
# Step 3
```
df = df.drop_duplicates()
```
This ensures clean training data.

## 📌 Quick Summary
```
Function	Purpose
duplicated()	Detect duplicate rows
df[df.duplicated()]	Show duplicates
drop_duplicates()	Remove duplicates
subset=	Check duplicates in specific columns
keep="first"	Keep first occurrence
keep="last"	Keep last occurrence
keep=False	Remove all duplicates
```
If you want, I can also give you the next README sections in the same professional style:

## 8️⃣ Data Transformation

## 9️⃣ GroupBy Operations

## 🔟 Merging & Joining DataFrames

These will make your GitHub notes look like a full Pandas documentation site.

## 8️⃣ Data Type Conversion
```
astype()

to_datetime()

to_numeric()

Category data type
```


## 🐼 Pandas Data Type Conversion

- Data type conversion is very important in Machine Learning preprocessing because ML models require numeric inputs.

- Real-world datasets often contain:

- Strings instead of numbers

- Dates stored as text

- Categories stored as objects

- Using Pandas, we convert them into ML-friendly formats.

## 8️⃣ Data Type Conversion
## 🔹 Why Data Type Conversion is Important

Machine Learning models cannot understand raw text or mixed data types.

## Example dataset:
```
Name	Age	Salary	Joining_Date
Aman	25	50000	2023-01-10
Riya	27	60000	2022-05-21
```
## For ML models:

Age → numeric

Salary → numeric

Joining_Date → datetime

Categorical columns → encoded

## 1️⃣ astype() – Change Data Type

Used to convert one data type into another.

## Syntax
df["column"] = df["column"].astype(new_type)
## Example
```
import pandas as pd

data = {
    "Age": ["25", "30", "35"]
}

df = pd.DataFrame(data)

print(df.dtypes)
```
## Output
```
Age    object
dtype: object
```
## Convert to integer
```
df["Age"] = df["Age"].astype(int)

print(df.dtypes)
```
## Output
```
Age    int64
dtype: object
Convert Multiple Columns
df = df.astype({
    "Age": "int64",
    "Salary": "float64"
})
```
Convert to String
```
df["Age"] = df["Age"].astype(str)
```
Common Data Types
```
Type	Description
int	Integer
float	Decimal numbers
str	String
bool	True / False
```
category	Memory efficient categorical data
## 2️⃣ to_datetime() – Convert to Date

> Datasets often contain dates stored as text.

## Example:
```
Date
2024-01-01
2024-02-10
```
Pandas converts them into datetime format.

## Example
```
data = {
    "Date": ["2024-01-01", "2024-02-10"]
}

df = pd.DataFrame(data)

df["Date"] = pd.to_datetime(df["Date"])

print(df.dtypes)
```
Output
```
Date    datetime64[ns]
dtype: object
````
Extract Date Components

After conversion you can extract useful features.
```
df["year"] = df["Date"].dt.year
df["month"] = df["Date"].dt.month
df["day"] = df["Date"].dt.day
```
## Example output
```
Date	year	month	day
2024-01-01	2024	1	1
2024-02-10	2024	2	10
```
## Why Important in ML?

Dates help create features like:
```
Month

Day

Weekday

Season
```
These improve model performance.

## 3️⃣ to_numeric() – Convert to Numbers

Sometimes numeric columns contain text values.

## Example dataset:
```
Salary
50000
60000
Unknown
```
Trying to convert directly causes errors.

## Example
```
data = {
    "Salary": ["50000", "60000", "Unknown"]
}

df = pd.DataFrame(data)

df["Salary"] = pd.to_numeric(df["Salary"], errors="coerce")

print(df)
```
## Output
```
   Salary
0  50000
1  60000
2   NaN
```
Explanation
Parameter	Meaning
errors="coerce"	Invalid values become NaN

This allows us to clean bad data automatically.

## 4️⃣ Category Data Type

Categorical data appears frequently in ML datasets.

## Example:
```
City
Delhi
Mumbai
Delhi
```
Default dtype:
```
object
```
Convert to category:
```
df["City"] = df["City"].astype("category")
```
Check Categories
```
print(df["City"].cat.categories)
```
Example output
```
Index(['Delhi', 'Mumbai'], dtype='object')
```
Why Category Type is Important

## Benefits:
```
✔ Saves memory
✔ Faster computations
✔ Useful for encoding features
```
## Example memory comparison:
```
Type	Memory
object	High
category	Low
```
For large datasets this dramatically improves performance.

## 🧠 Internal ML Workflow
```
Real ML preprocessing pipeline:

Raw Dataset
      ↓
Data Inspection
      ↓
Data Type Conversion
      ↓
Missing Value Handling
      ↓
Feature Engineering
      ↓
Model Training
```
## 🎯 Interview Questions

Common Pandas interview questions:

1️⃣ Difference between astype() and to_numeric()

2️⃣ Why is category type memory efficient?

3️⃣ What happens if to_datetime() fails?

4️⃣ How do you extract year from datetime?

5️⃣ Why must ML models use numeric features?

## 🚀 Summary
Concept	Purpose
```
astype()	Change data type
to_datetime()	Convert text → date
to_numeric()	Convert text → number
category	Memory-efficient categorical data
```
## 🔜 Next Topic

Next in the Pandas learning roadmap:

## 9️⃣ String Operations

We will learn:
```
.str.lower()
.str.upper()
.str.contains()
.str.replace()
.str.split()
```
These are extremely important for text preprocessing in ML datasets.

If you want, I can also give you a 🔥 complete GitHub repo structure for your Pandas ML notes like this:
```
pandas-ml-notes/
│
├── README.md
├── 01_pandas_basics.md
├── 02_data_inspection.md
├── 03_data_selection.md
├── 04_missing_values.md
├── 05_duplicates.md
├── 06_dtype_conversion.md
├── 07_string_operations.md
├── 08_groupby.md
├── 09_merge_join.md
├── 10_feature_engineering.md
└── projects/
```
This will make your repo look like real AI engineer documentation (very impressive in interviews). 🚀

## 9️⃣ String Operations

- .str.lower()

- .str.upper()

- .str.contains()

- .str.replace()

- .str.split()

Below is a clean, professional GitHub README.md documentation style section for Pandas String Operations.
It follows the same structure as your previous notes so your repo looks like real ML engineer documentation.

You can copy-paste directly into README.md.

🐼 Pandas String Operations

> In real-world datasets, text data is very common.

Examples:
```
Name	City
AMAN	Delhi
riya	Mumbai
John	Delhi
```
Before using data in Machine Learning, text columns must be cleaned and standardized.

Pandas provides the .str accessor to perform vectorized string operations on a column.

## 9️⃣ String Operations
## 🔹 What is .str ?

> .str allows you to apply string functions on Pandas Series.

## Example column:
```
df["Name"]
```
## Output
```
0    AMAN
1    riya
2    John
Name: Name, dtype: object
```
Now we can apply string operations:
```
df["Name"].str.method()
```
## 1️⃣ .str.lower() – Convert Text to Lowercase

Converts all characters in a column to lowercase.

Example
```
import pandas as pd

data = {
    "Name": ["AMAN", "Riya", "JOHN"]
}

df = pd.DataFrame(data)

df["Name"] = df["Name"].str.lower()

print(df)
```
## Output
```
    Name
0   aman
1   riya
2   john
```
## Why Important?

Standardizing text avoids duplicate categories.

## Example problem:
```
Delhi
DELHI
delhi
```
All represent the same value.

## 2️⃣ .str.upper() – Convert Text to Uppercase

Converts text to uppercase.

Example
```
df["Name"] = df["Name"].str.upper()
```
Output
```
    Name
0   AMAN
1   RIYA
2   JOHN
```
## 3️⃣ .str.contains() – Find Matching Text

Used for filtering rows containing a specific pattern.

## Syntax
```
df["column"].str.contains("pattern")
```
## Example Dataset
```
data = {
    "City": ["Delhi", "Mumbai", "New York", "Delhi"]
}

df = pd.DataFrame(data)
Find rows containing Delhi
df[df["City"].str.contains("Delhi")]
```
Output
```
    City
0   Delhi
3   Delhi
```
Case Insensitive Search
```
df[df["City"].str.contains("delhi", case=False)]
```
Useful when dataset contains mixed capitalization.

## 4️⃣ .str.replace() – Replace Text

Used to replace characters or words in a column.

## Example

## Dataset:

Name
Aman Kumar
Riya Sharma

## Remove last names:
```
df["Name"] = df["Name"].str.replace(" Kumar", "")
```
## Output
```
   Name
0  Aman
1  Riya Sharma
Replace Multiple Patterns
df["City"] = df["City"].str.replace("New York", "NY")
```
Output
```
NY
Delhi
Mumbai
```
## 5️⃣ .str.split() – Split Text

Used when a column contains multiple values in one string.

## Example dataset:
```
Full_Name
Aman Kumar
Riya Sharma
```
Split first and last names.

## Example
```
df[["First_Name","Last_Name"]] = df["Full_Name"].str.split(" ", expand=True)
```
Output
```
Full_Name	First_Name	Last_Name
Aman Kumar	Aman	Kumar
Riya Sharma	Riya	Sharma
Without Expanding
df["Full_Name"].str.split(" ")
```
Output
```
0    [Aman, Kumar]
1    [Riya, Sharma]
```
## 🔥 Real ML Use Cases

String operations are used in data cleaning pipelines.

Example tasks:

✔ Cleaning product names
✔ Standardizing categories
✔ Extracting information from text
✔ Preparing features for NLP models

Example ML workflow:
```
Raw Dataset
      ↓
Text Cleaning
      ↓
String Processing
      ↓
Feature Engineering
      ↓
Model Training
```
## 🧠 Internal Working

Pandas string operations are vectorized.

Instead of loops:

## ❌ Slow
```
for name in df["Name"]:
    print(name.lower())
```
## ✔ Fast
```
df["Name"].str.lower()
```
Vectorization makes Pandas very efficient for large datasets.

## 🎯 Interview Questions

Common Pandas interview questions:

- 1️⃣ What is .str accessor in Pandas?

- 2️⃣ Difference between .str.split() and Python split()?

- 3️⃣ Why should text be standardized before ML?

- 4️⃣ How to perform case-insensitive filtering?

- 5️⃣ How to split a column into multiple columns?

## 🚀 Summary
Function	Purpose
```
.str.lower()	Convert to lowercase
.str.upper()	Convert to uppercase
.str.contains()	Filter text patterns
.str.replace()	Replace words
.str.split()	Split text into columns
```
## 🔜 Next Topic

Next topic in your Pandas ML roadmap:

## 🔟 Column Operations

We will learn:

- Creating new columns
- Renaming columns
- Dropping columns
- Applying functions to columns

These operations are core to feature engineering in Machine Learning.

If you want, I can also help you build a 🔥 visually beautiful GitHub README (with badges, diagrams, collapsible sections, and navigation) so your Pandas notes look like a professional open-source documentation project.
---
# 1️⃣1️⃣ Apply & Lambda in Pandas

In real-world **data preprocessing** and **machine learning workflows**, we often need to transform or modify data values.

Pandas provides powerful functions for this:

- `.apply()`
- `.map()`
- `.applymap()`
- `lambda functions`

These allow us to apply **custom logic to columns, rows, or entire DataFrames**.

---

# 🔹 1️⃣ `.apply()`

`.apply()` is used to apply a **function to a column or row**.

It is commonly used for **feature transformation in ML pipelines**.

## Syntax

```python
df["column"].apply(function)
```

---

## Example Dataset

```python
import pandas as pd

data = {
    "Salary": [30000, 40000, 50000]
}

df = pd.DataFrame(data)

print(df)
```

### Output

```
   Salary
0  30000
1  40000
2  50000
```

---

## Example: Convert Salary to Thousands

```python
df["Salary_K"] = df["Salary"].apply(lambda x: x / 1000)

print(df)
```

### Output

```
   Salary  Salary_K
0  30000     30.0
1  40000     40.0
2  50000     50.0
```

---

## Example: Using Custom Function

```python
def categorize_salary(x):
    if x > 40000:
        return "High"
    else:
        return "Low"

df["Category"] = df["Salary"].apply(categorize_salary)

print(df)
```

### Output

```
   Salary Category
0  30000    Low
1  40000    Low
2  50000    High
```

---

# 🔹 2️⃣ `.map()`

`.map()` is used to **map values of a Series to new values**.

It is typically used for:

- Encoding categorical variables
- Replacing values

## Syntax

```python
df["column"].map(dictionary)
```

---

## Example

```python
data = {
    "Gender": ["M", "F", "F", "M"]
}

df = pd.DataFrame(data)

gender_map = {
    "M": "Male",
    "F": "Female"
}

df["Gender"] = df["Gender"].map(gender_map)

print(df)
```

### Output

```
   Gender
0   Male
1   Female
2   Female
3   Male
```

---

## Using Lambda with `.map()`

```python
df["Salary_K"] = df["Salary"].map(lambda x: x / 1000)
```

---

# 🔹 3️⃣ `.applymap()`

`.applymap()` applies a function to **every element of a DataFrame**.

Unlike `.apply()`, which works on **rows or columns**, `.applymap()` works on **individual cells**.

---

## Example

```python
data = {
    "A": [1, 2],
    "B": [3, 4]
}

df = pd.DataFrame(data)

df = df.applymap(lambda x: x * 10)

print(df)
```

### Output

```
    A   B
0  10  30
1  20  40
```

---

# 🔹 4️⃣ Lambda Functions

A **lambda function** is a small anonymous function.

It allows writing **short functions in one line**.

## Syntax

```python
lambda arguments: expression
```

---

## Example

```python
df["Salary_K"] = df["Salary"].apply(lambda x: x / 1000)
```

Meaning:

```
Take value x
Divide it by 1000
Return result
```

---

## Another Example

```python
df["Age_Group"] = df["Age"].apply(lambda x: "Adult" if x > 18 else "Minor")
```

### Output

```
   Age Age_Group
0  22    Adult
1  15    Minor
```

---

# 🔥 Real ML Use Cases

These functions are commonly used in **data preprocessing pipelines**.

| Task | Example |
|-----|------|
| Feature scaling | Convert salary to thousands |
| Encoding | Male → 1, Female → 0 |
| Feature engineering | Create Age groups |
| Data cleaning | Modify text or numbers |

Example ML workflow:

```
Raw Dataset
      ↓
Data Cleaning
      ↓
Feature Transformation
      ↓
Feature Engineering
      ↓
Model Training
```

---

# ⚡ Performance Tip

For large datasets:

- Prefer **vectorized operations**
- Avoid heavy use of `.apply()` loops

Example (faster):

```python
df["Salary_K"] = df["Salary"] / 1000
```

---

# 🎯 Interview Questions

1️⃣ Difference between `.apply()` and `.map()`  

2️⃣ When should `.applymap()` be used?  

3️⃣ What is a lambda function?  

4️⃣ Why is `.map()` useful for categorical encoding?  

5️⃣ Is `.apply()` faster than vectorized operations?

---

# 🚀 Summary

| Function | Use Case |
|------|------|
| `.apply()` | Apply function to rows or columns |
| `.map()` | Map values of a Series |
| `.applymap()` | Apply function to every DataFrame element |
| `lambda` | Short anonymous functions |

---

# 🔜 Next Topic

## 1️⃣2️⃣ GroupBy (VERY IMPORTANT FOR ML)

Topics covered next:

```
groupby()
mean()
sum()
count()
agg()
multiple aggregations
transform vs aggregate
```
# 1️⃣2️⃣ GroupBy (VERY IMPORTANT FOR ML)

`groupby()` is one of the **most powerful and commonly used operations in Pandas**.

It allows you to:

- Split data into groups
- Apply operations on each group
- Combine the results

This concept is often called **Split → Apply → Combine**.

---

# 🔹 What is GroupBy?

GroupBy allows us to **group rows based on column values and perform calculations on those groups**.

Example dataset:

| Department | Salary |
|-----------|--------|
| IT | 50000 |
| HR | 40000 |
| IT | 60000 |
| HR | 45000 |

Using `groupby()` we can compute statistics like:

- Average salary per department
- Total salary per department
- Number of employees per department

---

# 🔹 Syntax

```python
df.groupby("column")
```

Example:

```python
df.groupby("Department")
```

---

# 🔹 Example Dataset

```python
import pandas as pd

data = {
    "Department": ["IT", "HR", "IT", "HR", "Finance"],
    "Salary": [50000, 40000, 60000, 45000, 70000],
    "Age": [25, 30, 28, 35, 40]
}

df = pd.DataFrame(data)

print(df)
```

### Output

```
  Department  Salary  Age
0         IT   50000   25
1         HR   40000   30
2         IT   60000   28
3         HR   45000   35
4    Finance   70000   40
```

---

# 🔹 Aggregation Functions

Aggregation functions summarize grouped data.

Common aggregation functions:

- `mean()`
- `sum()`
- `count()`
- `min()`
- `max()`

---

# 1️⃣ `mean()` – Average

Calculate the **average value of each group**.

```python
df.groupby("Department")["Salary"].mean()
```

### Output

```
Department
Finance    70000
HR         42500
IT         55000
```

---

# 2️⃣ `sum()` – Total

Calculate the **total sum of values in each group**.

```python
df.groupby("Department")["Salary"].sum()
```

### Output

```
Department
Finance    70000
HR         85000
IT        110000
```

---

# 3️⃣ `count()` – Number of Rows

Count how many rows belong to each group.

```python
df.groupby("Department")["Salary"].count()
```

### Output

```
Department
Finance    1
HR         2
IT         2
```

---

# 4️⃣ `agg()` – Multiple Aggregations

`agg()` allows performing **multiple aggregation functions at once**.

### Example

```python
df.groupby("Department")["Salary"].agg(["mean", "sum", "count"])
```

### Output

```
            mean     sum  count
Department
Finance   70000   70000      1
HR        42500   85000      2
IT        55000  110000      2
```

---

# 🔹 Multiple Column Aggregations

We can aggregate **multiple columns simultaneously**.

```python
df.groupby("Department").agg({
    "Salary": ["mean", "sum"],
    "Age": ["min", "max"]
})
```

### Output

```
            Salary        Age
             mean   sum  min max
Department
Finance     70000 70000  40  40
HR          42500 85000  30  35
IT          55000 110000 25  28
```

---

# 🔹 GroupBy Multiple Columns

We can also group data using **multiple columns**.

```python
df.groupby(["Department", "Age"])["Salary"].mean()
```

This creates **hierarchical grouping**.

---

# 🔹 Transform vs Aggregate

Understanding the difference between **transform() and aggregation functions** is important.

---

## Aggregate

Aggregation **reduces data size**.

Example:

```python
df.groupby("Department")["Salary"].mean()
```

Output:

```
Department
Finance    70000
HR         42500
IT         55000
```

Rows become **group summaries**.

---

## Transform

Transform **keeps the same number of rows as the original dataset**.

Example:

```python
df["Dept_Avg_Salary"] = df.groupby("Department")["Salary"].transform("mean")

print(df)
```

### Output

```
  Department Salary Age Dept_Avg_Salary
0 IT         50000  25   55000
1 HR         40000  30   42500
2 IT         60000  28   55000
3 HR         45000  35   42500
4 Finance    70000  40   70000
```

---

# 🔥 Real ML Use Cases

GroupBy is extremely useful in **data analysis and feature engineering**.

Examples:

| Task | Example |
|-----|------|
| Sales analysis | Total sales per region |
| User analytics | Average purchase per user |
| Finance | Total revenue per department |
| Feature engineering | Customer purchase frequency |

Example ML pipeline:

```
Raw Dataset
      ↓
Data Cleaning
      ↓
Group Analysis
      ↓
Feature Engineering
      ↓
Model Training
```

---

# 🎯 Interview Questions

1️⃣ What is the purpose of `groupby()`?  

2️⃣ What is the **Split → Apply → Combine** concept?

3️⃣ Difference between **aggregate() and transform()**?

4️⃣ How do you perform **multiple aggregations**?

5️⃣ How to group by **multiple columns**?

---

# 🚀 Summary

| Function | Purpose |
|------|------|
| `groupby()` | Split dataset into groups |
| `mean()` | Average value |
| `sum()` | Total value |
| `count()` | Number of rows |
| `agg()` | Multiple aggregations |
| `transform()` | Return grouped values with same row count |

---

# 🔜 Next Topic

## 1️⃣3️⃣ Merging & Joining

Topics covered next:

```
merge()
inner join
left join
right join
outer join
join()
concat()
```

These operations are **very important for combining datasets in machine learning projects**.

This is **one of the most important Pandas topics for Data Science and Machine Learning.**
# 🔹 PHASE 5: Data Combining

In real-world data science and machine learning projects, data is often stored in **multiple datasets**.

For example:

- Customer dataset
- Orders dataset
- Product dataset

To perform analysis or build models, we must **combine these datasets**.

Pandas provides powerful tools for this:

- `merge()`
- `join()`
- `concat()`

These operations are **very important for feature engineering and ML pipelines**.

---

# 1️⃣3️⃣ Merging & Joining

## 🔹 `merge()`

`merge()` is used to **combine two DataFrames based on a common column (key)**.

It is similar to **SQL joins**.

### Syntax

```python
pd.merge(left_dataframe, right_dataframe, on="column", how="type")
```

Parameters:

| Parameter | Meaning |
|------|------|
| `left` | First DataFrame |
| `right` | Second DataFrame |
| `on` | Column used to merge |
| `how` | Type of join |

Join types:

- `inner`
- `left`
- `right`
- `outer`

---

# Example Datasets

### Employees Dataset

```python
import pandas as pd

employees = pd.DataFrame({
    "Employee_ID": [1,2,3,4],
    "Name": ["Aman","Riya","John","Sara"],
    "Department_ID": [101,102,101,103]
})
```

### Departments Dataset

```python
departments = pd.DataFrame({
    "Department_ID": [101,102,104],
    "Department_Name": ["IT","HR","Finance"]
})
```

---

# 🔹 1️⃣ Inner Join

Inner join returns **only matching rows from both datasets**.

### Example

```python
pd.merge(employees, departments, on="Department_ID", how="inner")
```

### Output

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
3            John      101           IT
2            Riya      102           HR
```

Rows with **Department_ID = 103 or 104 are excluded**.

---

# 🔹 2️⃣ Left Join

Left join returns:

- **All rows from the left DataFrame**
- Matching rows from the right DataFrame

### Example

```python
pd.merge(employees, departments, on="Department_ID", how="left")
```

### Output

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
2            Riya      102           HR
3            John      101           IT
4            Sara      103           NaN
```

`Sara` has no matching department.

---

# 🔹 3️⃣ Right Join

Right join returns:

- **All rows from the right DataFrame**
- Matching rows from the left DataFrame

### Example

```python
pd.merge(employees, departments, on="Department_ID", how="right")
```

### Output

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
3            John      101           IT
2            Riya      102           HR
NaN          NaN       104           Finance
```

Finance department has **no employees**.

---

# 🔹 4️⃣ Outer Join

Outer join returns **all rows from both DataFrames**.

Missing values are filled with `NaN`.

### Example

```python
pd.merge(employees, departments, on="Department_ID", how="outer")
```

### Output

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
2            Riya      102           HR
3            John      101           IT
4            Sara      103           NaN
NaN          NaN       104           Finance
```

---

# 🔹 Visual Join Comparison

| Join Type | Result |
|------|------|
| Inner | Only matching rows |
| Left | All rows from left |
| Right | All rows from right |
| Outer | All rows from both |

---

# 🔹 `join()`

`join()` is another method for combining DataFrames.

It is usually used when **joining based on index instead of columns**.

### Syntax

```python
df1.join(df2)
```

### Example

```python
employees.join(departments.set_index("Department_ID"), on="Department_ID")
```

This produces the **same result as a left merge**.

---

# 🔹 Concatenation

Concatenation means **stacking DataFrames together**.

It is done using:

```
pd.concat()
```

There are two main ways to concatenate:

1. Row-wise
2. Column-wise

---

# 🔹 Row-wise Concatenation

Stack datasets **vertically**.

### Example

```python
df1 = pd.DataFrame({
    "Name": ["Aman", "Riya"]
})

df2 = pd.DataFrame({
    "Name": ["John", "Sara"]
})

pd.concat([df1, df2])
```

### Output

```
Name
Aman
Riya
John
Sara
```

---

# 🔹 Column-wise Concatenation

Combine datasets **side-by-side**.

### Example

```python
df1 = pd.DataFrame({
    "Name": ["Aman", "Riya"]
})

df2 = pd.DataFrame({
    "Salary": [50000, 60000]
})

pd.concat([df1, df2], axis=1)
```

### Output

```
Name   Salary
Aman   50000
Riya   60000
```

`axis=1` means **combine columns**.

---

# 🔥 Importance in Feature Engineering

Combining datasets is essential in machine learning.

Example ML workflow:

```
Customer Dataset
        +
Transaction Dataset
        +
Product Dataset
        ↓
Merged Dataset
        ↓
Feature Engineering
        ↓
Machine Learning Model
```

Example features created after merging:

- Customer purchase frequency
- Average order value
- Total spending
- Product category preference

---

# ⚡ Performance Tips

When merging large datasets:

- Ensure **join keys are indexed**
- Avoid unnecessary columns
- Use **categorical data types**
- Clean duplicates before merging

---

# 🎯 Interview Questions

Common Pandas interview questions:

1️⃣ What is the difference between `merge()` and `join()`?

2️⃣ What is the difference between **inner join and outer join**?

3️⃣ When should we use `concat()` instead of `merge()`?

4️⃣ What happens if keys do not match?

5️⃣ Why is merging important in machine learning pipelines?

---

# 🚀 Summary

| Function | Purpose |
|------|------|
| `merge()` | Combine DataFrames using columns |
| `inner join` | Only matching rows |
| `left join` | All rows from left table |
| `right join` | All rows from right table |
| `outer join` | All rows from both tables |
| `join()` | Merge based on index |
| `concat()` | Stack DataFrames vertically or horizontally |

---

# 🔜 Next Topic

## 🔹 PHASE 6: Time Series (Important for AI)

### 1️⃣4️⃣ Working with Dates

Topics covered next:

```
Datetime conversion
Extracting:
year
month
day
weekday

Resampling

Rolling window

Expanding window
```

These are **very important for time-series ML models and forecasting projects**.

# 🔹 PHASE 5: Data Combining in Pandas

In real-world **data science, AI, and machine learning projects**, data rarely exists in a single file.

Instead, data is usually stored across **multiple datasets**, such as:

- Customer information
- Transactions
- Products
- Orders
- Locations
- Logs

To analyze this data or build machine learning models, we must **combine datasets**.

Pandas provides powerful tools for this:

| Method | Purpose |
|------|------|
| `merge()` | Combine DataFrames using columns |
| `join()` | Combine DataFrames using index |
| `concat()` | Stack DataFrames vertically or horizontally |

These operations are **critical for feature engineering and real-world ML pipelines**.

---

# 1️⃣3️⃣ Merging & Joining

## What is Data Merging?

Merging means **combining two or more datasets based on a common column**.

This concept is identical to **SQL JOIN operations**.

Example:

### Employees Table

| Employee_ID | Name | Department_ID |
|---|---|---|
| 1 | Aman | 101 |
| 2 | Riya | 102 |
| 3 | John | 101 |
| 4 | Sara | 103 |

### Departments Table

| Department_ID | Department_Name |
|---|---|
| 101 | IT |
| 102 | HR |
| 104 | Finance |

Goal:

Combine both tables to get:

| Name | Department |
|-----|-----|
| Aman | IT |
| Riya | HR |

This is done using **Pandas merge operations**.

---

# 🔹 Pandas `merge()` Function

The `merge()` function is the **most powerful method for combining datasets**.

### Syntax

```python
pd.merge(left_dataframe, right_dataframe, on="column", how="join_type")
```

### Parameters

| Parameter | Description |
|------|------|
| `left` | First DataFrame |
| `right` | Second DataFrame |
| `on` | Column used to join datasets |
| `how` | Type of join |

---

# 🔹 Types of Joins

There are **four major types of joins**.

| Join Type | Description |
|------|------|
| Inner Join | Only matching rows |
| Left Join | All rows from left dataset |
| Right Join | All rows from right dataset |
| Outer Join | All rows from both datasets |

---

# Example Dataset

```python
import pandas as pd

employees = pd.DataFrame({
    "Employee_ID": [1,2,3,4],
    "Name": ["Aman","Riya","John","Sara"],
    "Department_ID": [101,102,101,103]
})

departments = pd.DataFrame({
    "Department_ID": [101,102,104],
    "Department_Name": ["IT","HR","Finance"]
})
```

---

# 🔹 1️⃣ Inner Join

Inner join returns **only rows that exist in both datasets**.

### Syntax

```python
pd.merge(employees, departments, on="Department_ID", how="inner")
```

### Result

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
3            John      101           IT
2            Riya      102           HR
```

Explanation:

- Department 103 not present in departments
- Department 104 not present in employees

So those rows are removed.

---

# 🔹 2️⃣ Left Join

Left join returns:

- **All rows from left table**
- Matching rows from right table

### Syntax

```python
pd.merge(employees, departments, on="Department_ID", how="left")
```

### Result

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
2            Riya      102           HR
3            John      101           IT
4            Sara      103           NaN
```

Explanation:

Sara has **Department_ID 103**, but no matching department exists.

So Pandas inserts **NaN**.

---

# 🔹 3️⃣ Right Join

Right join returns:

- **All rows from right dataset**
- Matching rows from left dataset

### Syntax

```python
pd.merge(employees, departments, on="Department_ID", how="right")
```

### Result

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
3            John      101           IT
2            Riya      102           HR
NaN          NaN       104           Finance
```

Explanation:

Finance department has **no employees**, so values become **NaN**.

---

# 🔹 4️⃣ Outer Join

Outer join returns **all rows from both datasets**.

Missing values become **NaN**.

### Syntax

```python
pd.merge(employees, departments, on="Department_ID", how="outer")
```

### Result

```
Employee_ID  Name  Department_ID  Department_Name
1            Aman      101           IT
2            Riya      102           HR
3            John      101           IT
4            Sara      103           NaN
NaN          NaN       104           Finance
```

---

# 🔹 Visual Understanding of Joins

```
Inner Join
    A ∩ B

Left Join
    All A + Matching B

Right Join
    All B + Matching A

Outer Join
    A ∪ B
```

---

# 🔹 Merging on Different Column Names

Sometimes columns have **different names**.

Example:

```
customer_id
user_id
```

Use:

```python
pd.merge(df1, df2, left_on="customer_id", right_on="user_id")
```

---

# 🔹 Merging Multiple Columns

You can merge using **multiple keys**.

Example:

```python
pd.merge(df1, df2, on=["City","Date"])
```

---

# 🔹 Handling Duplicate Keys

If duplicate keys exist, Pandas creates **Cartesian product rows**.

Example:

```
CustomerID
1
1
```

May produce **multiple rows after merge**.

Always check:

```python
df.duplicated()
```

before merging.

---

# 🔹 Pandas `join()` Function

`join()` is another way to combine DataFrames.

It works primarily with **index-based merging**.

### Syntax

```python
df1.join(df2)
```

### Example

```python
employees.join(
    departments.set_index("Department_ID"),
    on="Department_ID"
)
```

This behaves like a **left join**.

---

# 🔹 Concatenation (`concat()`)

Concatenation means **stacking datasets together**.

It is useful when:

- Combining multiple datasets
- Appending new rows
- Creating larger datasets

### Syntax

```python
pd.concat([df1, df2])
```

---

# 🔹 Row-wise Concatenation (Vertical)

Combine datasets **top-to-bottom**.

### Example

```python
df1 = pd.DataFrame({
    "Name": ["Aman", "Riya"]
})

df2 = pd.DataFrame({
    "Name": ["John", "Sara"]
})

pd.concat([df1, df2])
```

### Result

```
Name
Aman
Riya
John
Sara
```

---

# 🔹 Column-wise Concatenation (Horizontal)

Combine datasets **side-by-side**.

### Example

```python
df1 = pd.DataFrame({
    "Name": ["Aman","Riya"]
})

df2 = pd.DataFrame({
    "Salary": [50000,60000]
})

pd.concat([df1, df2], axis=1)
```

### Result

```
Name   Salary
Aman   50000
Riya   60000
```

`axis=1` means **combine columns**.

---

# 🔹 Ignore Index Option

When concatenating rows:

```python
pd.concat([df1, df2], ignore_index=True)
```

This resets row numbering.

---

# 🔥 Importance in Machine Learning

Merging datasets is essential in ML workflows.

Example pipeline:

```
Customer Dataset
        +
Transaction Dataset
        +
Product Dataset
        ↓
Merged Dataset
        ↓
Feature Engineering
        ↓
Machine Learning Model
```

Examples of features created:

- Customer purchase frequency
- Average order value
- Total spending
- Product preferences
- Region-based demand

---

# ⚡ Performance Optimization Tips

For large datasets:

✔ Ensure join columns are indexed  

```
df.set_index("column")
```

✔ Remove unnecessary columns before merging  

✔ Use categorical data types  

✔ Avoid duplicate keys  

✔ Use appropriate join type  

---

# 🎯 Interview Questions

1️⃣ Difference between `merge()` and `join()`  

2️⃣ Difference between **inner join and outer join**  

3️⃣ When should we use `concat()` instead of `merge()`  

4️⃣ What happens if merge keys are duplicated  

5️⃣ How does Pandas handle missing values after merge  

6️⃣ How to merge datasets with different column names  

---

# 🚀 Summary

| Operation | Purpose |
|------|------|
| `merge()` | Combine DataFrames using columns |
| `inner join` | Only matching rows |
| `left join` | All rows from left dataset |
| `right join` | All rows from right dataset |
| `outer join` | All rows from both datasets |
| `join()` | Merge using index |
| `concat()` | Stack datasets vertically or horizontally |

---

# 🔜 Next Topic

## 🔹 PHASE 6: Time Series Analysis

### 1️⃣4️⃣ Working with Dates

Topics include:

- Datetime conversion
- Extracting year/month/day
- Weekday extraction
- Resampling
- Rolling windows
- Expanding windows

These concepts are **critical for time-series ML models such as sales forecasting, stock prediction, and demand forecasting**.
# 🔹 PHASE 6: Time Series Analysis in Pandas (Important for AI/ML)

Time series data is **data recorded over time**.

Examples:

| Date | Sales |
|-----|------|
| 2024-01-01 | 500 |
| 2024-01-02 | 650 |
| 2024-01-03 | 700 |

Time series analysis is widely used in:

- Stock market prediction
- Sales forecasting
- Demand prediction
- Weather forecasting
- Sensor data analysis
- Log monitoring
- Financial analytics

Pandas provides powerful tools to **handle and analyze time-based datasets**.

Key concepts include:

- Datetime conversion
- Extracting time components
- Resampling
- Rolling windows
- Expanding windows

---

# 1️⃣4️⃣ Working with Dates in Pandas

## Why Dates Matter in Machine Learning

Most real-world datasets contain **time-related information**.

Examples:

| Feature | Meaning |
|------|------|
| Purchase Date | Customer buying behavior |
| Transaction Time | Fraud detection |
| Timestamp | Sensor readings |
| Log time | System monitoring |

Before using them in ML models, we must **convert and engineer time-based features**.

---

# 🔹 Datetime Conversion

Datasets usually store dates as **strings**.

Example:

```
"2024-03-01"
```

Machine learning models cannot understand strings directly.

So we convert them into **datetime format**.

### Syntax

```python
pd.to_datetime(column)
```

---

## Example

```python
import pandas as pd

data = {
    "Date": ["2024-01-01", "2024-01-02", "2024-01-03"],
    "Sales": [500, 650, 700]
}

df = pd.DataFrame(data)

df["Date"] = pd.to_datetime(df["Date"])

print(df)
```

Output

```
        Date  Sales
0 2024-01-01   500
1 2024-01-02   650
2 2024-01-03   700
```

Now Pandas recognizes it as **datetime64 data type**.

---

# 🔹 Extracting Date Components

Once a column is converted to datetime, we can extract useful components.

This is **very important for feature engineering**.

Common extracted features:

| Feature | Example |
|------|------|
| Year | 2024 |
| Month | 3 |
| Day | 15 |
| Weekday | Monday |

---

# Extract Year

```python
df["Year"] = df["Date"].dt.year
```

Output

```
Date        Sales   Year
2024-01-01   500    2024
2024-01-02   650    2024
```

---

# Extract Month

```python
df["Month"] = df["Date"].dt.month
```

Output

```
Date        Month
2024-01-01    1
2024-01-02    1
```

---

# Extract Day

```python
df["Day"] = df["Date"].dt.day
```

---

# Extract Weekday

```python
df["Weekday"] = df["Date"].dt.day_name()
```

Output

```
Date        Weekday
2024-01-01  Monday
2024-01-02  Tuesday
```

This is useful for detecting **weekly sales patterns**.

---

# 🔹 Resampling

Resampling means **changing the frequency of time-series data**.

Example conversions:

| Original Data | Resampled Data |
|------|------|
| Hourly data | Daily data |
| Daily data | Monthly data |
| Monthly data | Yearly data |

---

### Syntax

```python
df.resample("rule")
```

Common rules:

| Rule | Meaning |
|------|------|
| D | Daily |
| W | Weekly |
| M | Monthly |
| Y | Yearly |
| H | Hourly |

---

## Example Dataset

```python
df = pd.DataFrame({
    "Date": pd.date_range("2024-01-01", periods=10),
    "Sales": [100,120,130,140,150,160,170,180,190,200]
})

df.set_index("Date", inplace=True)
```

---

# Monthly Resampling

```python
df.resample("M").sum()
```

This groups all values **by month**.

---

# Weekly Resampling

```python
df.resample("W").mean()
```

This calculates **weekly average sales**.

---

# 🔹 Rolling Window

Rolling windows calculate statistics **over a moving window of data**.

Example:

Compute average sales for the **last 3 days**.

---

### Syntax

```python
df["Sales"].rolling(window_size)
```

---

## Example

```python
df["Rolling_Avg"] = df["Sales"].rolling(3).mean()
```

Output

```
Sales   Rolling_Avg
100      NaN
120      NaN
130      116.6
140      130
150      140
```

Explanation:

Rolling average of **last 3 values**.

---

# Rolling Sum

```python
df["Rolling_Sum"] = df["Sales"].rolling(3).sum()
```

---

# Rolling Standard Deviation

```python
df["Rolling_STD"] = df["Sales"].rolling(3).std()
```

---

# 🔹 Expanding Window

Expanding windows compute statistics **from the beginning of the dataset**.

Unlike rolling windows, the window **continually grows**.

---

### Syntax

```python
df["Sales"].expanding()
```

---

## Example

```python
df["Expanding_Mean"] = df["Sales"].expanding().mean()
```

Output

```
Sales  Expanding_Mean
100        100
120        110
130        116
140        122
150        128
```

Explanation:

Mean calculated from **start of dataset to current row**.

---

# 🔹 Rolling vs Expanding

| Feature | Rolling | Expanding |
|------|------|------|
| Window Size | Fixed | Growing |
| Data Used | Recent values | Entire history |
| Use Case | Short-term trends | Long-term averages |

---

# 🔥 Real Machine Learning Use Cases

Time series features are extremely valuable.

Examples:

| Feature | Purpose |
|------|------|
| Day of week | Detect weekend sales |
| Month | Seasonal trends |
| Rolling mean | Short-term trends |
| Expanding mean | Long-term trends |

---

# Example ML Feature Engineering

```
Date
 ↓
Extract Features
 ↓
Year
Month
Day
Weekday
 ↓
Rolling Statistics
 ↓
Expanding Statistics
 ↓
Machine Learning Model
```

---

# ⚡ Performance Tips

✔ Always convert dates using `pd.to_datetime()`  

✔ Set datetime column as index for resampling  

```
df.set_index("Date", inplace=True)
```

✔ Use vectorized `.dt` operations  

✔ Avoid manual loops for date processing  

---

# 🎯 Interview Questions

1️⃣ What is time series data?

2️⃣ Difference between **rolling window and expanding window**?

3️⃣ What is **resampling** in Pandas?

4️⃣ How do you extract **year/month/day** from datetime?

5️⃣ Why are time-based features important for ML?

6️⃣ What is the difference between **rolling mean and expanding mean**?

---

# 🚀 Summary

| Concept | Purpose |
|------|------|
| `to_datetime()` | Convert strings to datetime |
| `.dt.year` | Extract year |
| `.dt.month` | Extract month |
| `.dt.day` | Extract day |
| `.dt.day_name()` | Extract weekday |
| `resample()` | Change time frequency |
| `rolling()` | Moving window statistics |
| `expanding()` | Cumulative statistics |

---

# 🔜 Next Topic

## 🔹 PHASE 7: Advanced Pandas for Machine Learning

### 1️⃣5️⃣ Pivot Tables

Topics include:

```
pivot()
pivot_table()
crosstab()
```

These tools help create **powerful data summaries used in EDA and feature engineering**.
# 🔹 PHASE 7: Advanced Pandas for Machine Learning

Advanced Pandas operations help transform raw datasets into **structured insights for machine learning**.

One of the most powerful tools for **data summarization and analysis** is the **Pivot Table**.

Pivot tables help to:

- Summarize large datasets
- Perform aggregation
- Compare multiple categories
- Prepare features for ML models
- Perform Exploratory Data Analysis (EDA)

Pandas provides three powerful functions:

| Function | Purpose |
|------|------|
| `pivot()` | Reshape data |
| `pivot_table()` | Aggregate and summarize data |
| `crosstab()` | Frequency table for categorical variables |

---

# 1️⃣5️⃣ Pivot Tables in Pandas

Pivot tables allow you to **reorganize and summarize datasets**.

They work similarly to **Excel Pivot Tables**.

Example dataset:

| Name | Department | Gender | Salary |
|-----|-----|-----|-----|
| Aman | IT | M | 50000 |
| Riya | HR | F | 60000 |
| John | IT | M | 55000 |
| Sara | HR | F | 65000 |

Goal:

Find **average salary by department and gender**.

---

# 🔹 1️⃣ `pivot()`

`pivot()` reshapes the data by turning **unique values from one column into new columns**.

It **does NOT perform aggregation**.

---

## Syntax

```python
df.pivot(index, columns, values)
```

| Parameter | Meaning |
|------|------|
| index | Rows |
| columns | Columns |
| values | Data values |

---

## Example Dataset

```python
import pandas as pd

data = {
    "Date": ["2024-01","2024-01","2024-02","2024-02"],
    "Product": ["Laptop","Phone","Laptop","Phone"],
    "Sales": [1000,500,1200,700]
}

df = pd.DataFrame(data)
print(df)
```

Dataset

```
Date     Product  Sales
2024-01  Laptop   1000
2024-01  Phone     500
2024-02  Laptop   1200
2024-02  Phone     700
```

---

## Using `pivot()`

```python
df.pivot(index="Date", columns="Product", values="Sales")
```

Output

```
Product   Laptop   Phone
Date
2024-01    1000      500
2024-02    1200      700
```

Explanation:

- `Date` becomes row index
- `Product` becomes columns
- `Sales` becomes values

---

# Important Limitation of `pivot()`

Pivot requires **unique combinations of index and column values**.

If duplicates exist, Pandas raises an error.

Example duplicate case:

```
Date Product Sales
2024-01 Laptop 1000
2024-01 Laptop 1200
```

Solution: Use **pivot_table() instead**.

---

# 🔹 2️⃣ `pivot_table()`

`pivot_table()` is a **more powerful version of pivot()**.

It allows:

- Aggregation
- Duplicate handling
- Multiple functions

---

## Syntax

```python
pd.pivot_table(
    df,
    values="column",
    index="row",
    columns="column",
    aggfunc="function"
)
```

---

## Example Dataset

```python
data = {
    "Department": ["IT","IT","HR","HR","Finance"],
    "Gender": ["M","F","M","F","F"],
    "Salary": [50000,60000,55000,65000,70000]
}

df = pd.DataFrame(data)
```

Dataset

```
Department Gender Salary
IT         M      50000
IT         F      60000
HR         M      55000
HR         F      65000
Finance    F      70000
```

---

## Average Salary by Department and Gender

```python
pd.pivot_table(
    df,
    values="Salary",
    index="Department",
    columns="Gender",
    aggfunc="mean"
)
```

Output

```
Gender        F        M
Department
Finance    70000     NaN
HR         65000    55000
IT         60000    50000
```

---

# Multiple Aggregation Functions

You can compute multiple statistics.

```python
pd.pivot_table(
    df,
    values="Salary",
    index="Department",
    aggfunc=["mean","sum","count"]
)
```

Output

```
           mean   sum   count
Department
Finance   70000 70000    1
HR        60000 120000   2
IT        55000 110000   2
```

---

# Filling Missing Values

Use `fill_value`.

```python
pd.pivot_table(
    df,
    values="Salary",
    index="Department",
    columns="Gender",
    fill_value=0
)
```

---

# Adding Totals

Use `margins=True`.

```python
pd.pivot_table(
    df,
    values="Salary",
    index="Department",
    columns="Gender",
    margins=True
)
```

This adds **overall totals**.

---

# 🔹 3️⃣ Crosstab

`crosstab()` is used to compute **frequency tables**.

It is especially useful for **categorical data analysis**.

---

## Syntax

```python
pd.crosstab(row_variable, column_variable)
```

---

## Example Dataset

```python
data = {
    "Gender": ["M","F","M","F","F","M"],
    "Purchased": ["Yes","No","Yes","Yes","No","Yes"]
}

df = pd.DataFrame(data)
```

Dataset

```
Gender Purchased
M      Yes
F      No
M      Yes
F      Yes
F      No
M      Yes
```

---

## Crosstab Example

```python
pd.crosstab(df["Gender"], df["Purchased"])
```

Output

```
Purchased   No   Yes
Gender
F           2     1
M           0     3
```

Explanation:

Counts occurrences of each combination.

---

# Normalized Crosstab (Percentage)

```python
pd.crosstab(
    df["Gender"],
    df["Purchased"],
    normalize=True
)
```

Returns **probability distribution**.

---

# Adding Margins

```python
pd.crosstab(
    df["Gender"],
    df["Purchased"],
    margins=True
)
```

Adds **totals row and column**.

---

# Pivot vs Pivot Table vs Crosstab

| Function | Purpose |
|------|------|
| `pivot()` | Reshape data |
| `pivot_table()` | Aggregate and summarize |
| `crosstab()` | Frequency table |

---

# 🔥 Importance in Machine Learning

Pivot tables help with **EDA and feature engineering**.

Examples:

| Use Case | Example |
|------|------|
| Sales analysis | Sales by region |
| Customer analysis | Purchases by gender |
| Marketing | Campaign response rate |
| Product analysis | Sales by category |

Example ML pipeline:

```
Raw Dataset
      ↓
Data Cleaning
      ↓
Pivot Analysis
      ↓
Feature Engineering
      ↓
Machine Learning Model
```

---

# ⚡ Performance Tips

✔ Use `pivot_table()` when duplicates exist  

✔ Use categorical data types for large datasets  

✔ Avoid large pivot tables with too many categories  

✔ Use `fill_value` to avoid missing values  

---

# 🎯 Interview Questions

1️⃣ Difference between `pivot()` and `pivot_table()`  

2️⃣ When should we use `crosstab()`?  

3️⃣ Why does `pivot()` fail with duplicate values?  

4️⃣ How do you add totals to a pivot table?  

5️⃣ How do you calculate percentage distribution using crosstab?

---

# 🚀 Summary

| Concept | Purpose |
|------|------|
| `pivot()` | Reshape data |
| `pivot_table()` | Aggregated pivot table |
| `crosstab()` | Frequency table |

---

# 🔜 Next Topic

## 1️⃣6️⃣ Window Functions

Important topics:

```
Rolling mean
Rolling sum
Expanding mean
```

These functions are **widely used in time-series ML models and financial data analysis**.
# 1️⃣6️⃣ Window Functions in Pandas

Window functions are powerful tools used to compute **statistics over a moving subset of data**.

Instead of calculating values using the entire dataset, window functions operate on a **specific window (subset) of rows**.

These are extremely important in:

- Time-series analysis
- Stock market prediction
- Sales forecasting
- Financial analytics
- Feature engineering for ML

Common window functions include:

| Function | Purpose |
|------|------|
| Rolling Mean | Moving average |
| Rolling Sum | Moving total |
| Expanding Mean | Cumulative average |

---

# 🔹 What is a Window?

A **window** refers to a subset of consecutive rows used for calculations.

Example dataset:

| Day | Sales |
|----|----|
| 1 | 100 |
| 2 | 120 |
| 3 | 130 |
| 4 | 150 |
| 5 | 170 |

If the window size is **3**, calculations will be performed on **3 consecutive rows at a time**.

---

# 🔹 Rolling Window

Rolling windows compute statistics using a **fixed-size sliding window**.

Example window size = 3:

```
[100,120,130]
   [120,130,150]
      [130,150,170]
```

---

# Rolling Mean (Moving Average)

Rolling mean calculates the **average of values within the window**.

This is commonly used in:

- Stock price smoothing
- Sales trend analysis
- Signal processing
- ML feature engineering

---

## Syntax

```python
df["column"].rolling(window_size).mean()
```

---

## Example

```python
import pandas as pd

data = {
    "Sales": [100,120,130,150,170]
}

df = pd.DataFrame(data)

df["Rolling_Mean"] = df["Sales"].rolling(3).mean()

print(df)
```

Output

```
Sales  Rolling_Mean
100      NaN
120      NaN
130     116.67
150     133.33
170     150.00
```

Explanation:

Rolling average of the **last 3 values**.

First two rows return **NaN** because a full window isn't available.

---

# 🔹 Rolling Sum

Rolling sum calculates the **sum of values within the window**.

This is useful for:

- Total sales in recent days
- Short-term financial metrics
- Moving transaction totals

---

## Syntax

```python
df["column"].rolling(window_size).sum()
```

---

## Example

```python
df["Rolling_Sum"] = df["Sales"].rolling(3).sum()
```

Output

```
Sales  Rolling_Sum
100      NaN
120      NaN
130      350
150      400
170      450
```

Explanation:

Example:

```
100 + 120 + 130 = 350
```

---

# 🔹 Expanding Window

Expanding windows compute statistics **from the beginning of the dataset up to the current row**.

Unlike rolling windows, the window **keeps growing**.

Example expanding windows:

```
[100]
[100,120]
[100,120,130]
[100,120,130,150]
```

---

# Expanding Mean

Expanding mean calculates the **cumulative average**.

---

## Syntax

```python
df["column"].expanding().mean()
```

---

## Example

```python
df["Expanding_Mean"] = df["Sales"].expanding().mean()
```

Output

```
Sales  Expanding_Mean
100        100
120        110
130        116.67
150        125
170        134
```

Explanation:

Mean calculated from **first value up to current value**.

---

# 🔹 Rolling vs Expanding

| Feature | Rolling | Expanding |
|------|------|------|
| Window Size | Fixed | Growing |
| Data Used | Recent values | Entire history |
| Use Case | Short-term trends | Long-term trends |

---

# 🔹 Visualization Example

Sales data:

```
100 120 130 150 170
```

Rolling mean (window=3):

```
NaN NaN 116 133 150
```

Expanding mean:

```
100 110 116 125 134
```

---

# 🔥 Real Machine Learning Use Cases

Window functions are used to create **powerful predictive features**.

Examples:

| Feature | Description |
|------|------|
| 7-day rolling sales | Recent demand trend |
| 30-day rolling average | Monthly demand |
| Expanding revenue mean | Overall performance trend |

---

# Example ML Feature Engineering

```
Sales Dataset
      ↓
Rolling Mean (7 days)
      ↓
Rolling Sum (30 days)
      ↓
Expanding Mean
      ↓
Machine Learning Model
```

---

# 🔹 Advanced Rolling Operations

Rolling windows support many statistics.

Examples:

### Rolling Minimum

```python
df["Sales"].rolling(3).min()
```

### Rolling Maximum

```python
df["Sales"].rolling(3).max()
```

### Rolling Standard Deviation

```python
df["Sales"].rolling(3).std()
```

---

# 🔹 Handling Missing Values

Rolling functions return **NaN for early rows**.

You can fill them using:

```python
df.fillna(0)
```

or

```python
df["Rolling_Mean"].fillna(method="bfill")
```

---

# 🔹 Window Functions with Time-Series Index

These functions work best when the dataset has a **datetime index**.

Example:

```python
df["Date"] = pd.to_datetime(df["Date"])

df.set_index("Date", inplace=True)
```

Now rolling windows work correctly on **time-based data**.

---

# ⚡ Performance Tips

✔ Use vectorized operations  

✔ Avoid loops for moving calculations  

✔ Use datetime index for time-series datasets  

✔ Use appropriate window sizes  

---

# 🎯 Interview Questions

1️⃣ What is a rolling window?

2️⃣ Difference between rolling mean and expanding mean?

3️⃣ Why do rolling functions return NaN?

4️⃣ How are window functions used in time-series ML?

5️⃣ What is the difference between rolling window and resampling?

---

# 🚀 Summary

| Function | Purpose |
|------|------|
| `rolling().mean()` | Moving average |
| `rolling().sum()` | Moving total |
| `expanding().mean()` | Cumulative average |

---

# 🔜 Next Topic

## 🔹 PHASE 7: Performance Optimization

Topics include:

```
Vectorization
Avoid loops
Memory usage optimization
Using categorical data
```

These techniques help **speed up Pandas operations on large datasets**.
