# File Handling in Python: Count Lines Not Starting with 'T'

## Aim
To write a Python program to read a file and count the frequency of each character in  it.
##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```
from collections import defaultdict


def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def char_frequency(file_path):
    with open(file_path,'r')as file:
        content=file.read()
    frequency=defaultdict(int)
    for char in content:
        frequency[char]+=1
    return freuquency
```


## Output
![files](https://github.com/user-attachments/assets/a3efa096-b260-4e00-85de-a0fae0220d5c)

## Result
Thus a Python program to read a file and count the frequency of each character in it is created.

