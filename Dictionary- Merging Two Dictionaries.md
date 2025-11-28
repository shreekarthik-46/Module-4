## 4) b) Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program
```
dict1=eval(input())
dict2=eval(input())
for i in dict1:
    dict2[i]=dict1[i]
print(dict2)
```


## Output

![mer-dict](https://github.com/user-attachments/assets/0e5a73c5-e665-47c8-9767-0afe9902c6cc)

## Result
Thus a Python program that merges **two dictionaries** and combines their key-value pairs is created.
