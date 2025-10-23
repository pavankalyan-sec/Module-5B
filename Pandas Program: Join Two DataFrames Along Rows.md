# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

~~~
import pandas as pd
data1 = {
    'Name': ['Alice', 'Bob'],
    'Age': [24, 27],
    'City': ['New York', 'Los Angeles']
}
data2 = {
    'Name': ['Charlie', 'David'],
    'Age': [22, 29],
    'City': ['Chicago', 'San Francisco']
}

df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)
result_df = pd.concat([df1, df2], axis=0, ignore_index=True)
print("Concatenated DataFrame:")
print(result_df)
~~~

## Output
<img width="675" height="315" alt="image" src="https://github.com/user-attachments/assets/ba563078-3470-4351-ae84-2f04fa03e172" />

## Result
Thus, the program has been executed successfully.
