# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
data = {
    "Banana": 3,
    "Apple": 5,
    "Cherry": 2,
    "Date": 4
}
sorted_by_keys = dict(sorted(data.items()))
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))
print(f"Original Dictionary: {data}")
print(f"Sorted by Keys:      {sorted_by_keys}")
print(f"Sorted by Values:    {sorted_by_values}")

## Sample Output
Original Dictionary:  {"Banana": 3,"Apple": 5,"Cherry": 2,"Date": 4}
Sorted by Keys: {"Banana","Apple","Cherry","Data"}
Sorted by Values: {3,5,2,4}
## Result
Thus,the python program was run successsfully for the given question
