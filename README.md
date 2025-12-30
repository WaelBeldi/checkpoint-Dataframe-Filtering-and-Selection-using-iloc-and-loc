# What You're Aiming For

The objective is to enhance proficiency in manipulating pandas DataFrames by creating and querying datasets using iloc for index-based selections and loc for label-based filtering.

---

## Instructions

In this exercise, you will work with a dataset called "employee info" that contains information about employees in a company. The dataset includes columns such as Name, Department, Age, Gender, Salary, and Experience.

Create a dataframe called "employee_df" with the following data:

```python
import pandas as pd

data = {
    'Name': ['John', 'Mary', 'Bob', 'Sarah', 'Tom', 'Lisa'],
    'Department': ['IT', 'Marketing', 'Sales', 'IT', 'Finance', 'Marketing'],
    'Age': [30, 40, 25, 35, 45, 28],
    'Gender': ['Male', 'Female', 'Male', 'Female', 'Male', 'Female'],
    'Salary': [50000, 60000, 45000, 55000, 70000, 55000],
    'Experience': [3, 7, 2, 5, 10, 4]
}

employee_df = pd.DataFrame(data)
```

1. Use the `iloc` method to select the first 3 rows of the dataframe.
2. Use the `loc` method to select all rows where the Department is "Marketing".
3. Use the `iloc` method to select the Age and Gender columns for the first 4 rows of the dataframe.
4. Use the `loc` method to select the Salary and Experience columns for all rows where the Gender is "Male".

---

### Note:

* `iloc` is used for selection by index location
* `loc` is used for selection by label.
