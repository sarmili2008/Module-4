# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
with open("story.txt", "r") as file:
    count = 0
    for line in file:
        if line and not line.startswith('T'):
            count += 1
print(f"Number of lines that do not start with 'T': {count}")

## Output
The sky was blue.
Trees swayed in the wind.
Birds were flying south.
Today was a warm day.
An owl hooted loudly.
Number of lines that do not start with 'T': 2
## Result
Thus,the python program was run successfully for the given question
