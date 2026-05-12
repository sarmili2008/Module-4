## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
dict1 = eval(input())
dict2 = eval(input())
merged_dict = {**dict1, **dict2}
print(merged_dict)

## Output
{1:10,2:20,3:30}
{5:50,2:"two"}
{1: 10, 2: 'two', 3: 30, 5: 50}
## Result
Thus,the python program was run successfully for the given question
