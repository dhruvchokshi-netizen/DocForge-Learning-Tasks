Yes. This is a **strong Week 1**.

Not overwhelming. Not toy-level. Not “copy-paste Kaggle.”
It builds foundation bricks instead of throwing them into model training chaos.

Let me structure this cleanly for you 👇

---

# 🗓 Week 1 Structure

You’ll give:

* **Task 1A → Data Handling & Workflow**
* **Task 1B → ML Thinking Basics**

Week 1 goal is not “build AI.”
Week 1 goal is:

> Understand what data is and how ML *thinks*.

That’s powerful.

---

# 📁 WEEK 1 – TASK 1A

## Python, Pandas, Preprocessing & Git Basics

### 🎯 Objective

Understand how raw data is transformed into ML-ready data.

You will learn:

* How to explore datasets
* How to clean data
* Why preprocessing matters
* How version control fits into ML workflows

---

## 📊 Dataset

**Student Performance Dataset**

You may use:

* Kaggle: Students Performance in Exams ([Click here](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams))

---

## 📚 Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import StandardScaler, MinMaxScaler
```

---

## 🔹 Task 1.1 – Data Exploration & Cleaning

### Step 1: Load the Dataset

Using pandas:

* Display first 5 rows
* Print column names
* Print dataset shape
* Print data types

---

### Step 2: Handle Missing Values

* Check for missing values
* Either drop OR fill them
* Explain your decision in markdown

---

### Step 3: Standardize Column Names

* Convert to lowercase
* Replace spaces with `_`

Example:

```
Parental Level of Education → parental_level_of_education
```

---

### Step 4: Clean Categorical Data

Convert at least one categorical column to lowercase.

---

### Step 5: Basic Analysis

Find:

* Top 10 students based on total score
* Average score grouped by:

  * gender OR
  * parental education OR
  * lunch type

Write 2–3 short observations.

---

## 📈 Task 1.2 – Visualization & Insights

Create at least two plots:

1️⃣ Score distribution histogram
2️⃣ Bar chart of average score by category
3️⃣ Optional: Correlation heatmap

After plotting, write 2–3 insights such as:

* Are scores normally distributed?
* Which group performs better?
* Are subjects correlated?

---

## ⚙️ Task 1.3 – Feature Engineering & Preprocessing

### Create a New Feature

Choose one:

```
total_score = math + reading + writing
```

OR

```
effort_score = study_time / (absences + 1)
```

Explain why this might help a model.

---

### Encode Categorical Columns

* yes/no → 1/0
  OR
* Use one-hot encoding

---

### Scale Numeric Features

Use:

* StandardScaler
  OR
* MinMaxScaler

Explain:
Why do ML models require scaling?

---

### Save Final Dataset

Save as:

```
processed.csv
```

---

## 🌿 Task 1.4 – Git Practice

1️⃣ Create branch:

```
git checkout -b fun
```

2️⃣ Upload a screenshot from your favorite movie
(Movie name must NOT appear in image)

3️⃣ Create file:

```
movie.env
```

Inside:

```
MOVIE_NAME=YourMovieName
```

4️⃣ Add `movie.env` to `.gitignore`

Ensure it is NOT pushed.

---

## 📦 Submission Structure

```
week1/
│
├── task1A/
│   ├── notebook.ipynb
│   ├── processed.csv (optional)
│   ├── explanation.md

```

---