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
```
with open("story.txt","r") as f:
   count=0
   a=f.read().split("\n")
   for i in a:
      if not i.startswith("T"):
         count+=1
print('The number of lines that doesn\'t starts with "T" :',count)
   
```

## Output

<img width="1727" height="368" alt="image" src="https://github.com/user-attachments/assets/ecb7eabd-677b-4a72-9cd4-b6d392065dbe" />

## Result
program has been successfully completed
