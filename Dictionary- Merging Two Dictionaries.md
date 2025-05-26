## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

~~~

dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'c': 30, 'd': 40}
def merge(d1, d2):
    return {**d1, **d2}  
merged_dict = merge(dict1, dict2)
print("Merged dictionary:", merged_dict)

~~~

## Output
![Screenshot (190)](https://github.com/user-attachments/assets/23594d74-8c52-4ef7-9477-fe1edeb8e313)

## Result
Therefore,the given python program is successfully verified
