# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.

## Equipment’s required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Get the list of marks as input
2. Use the sort() function or max() function or use the for loop to find the maximum mark.
3. Return the maximum value

## Program:
i) # To find the maximum of marks using the list method sort.
```Python
# Program to mark the maximum of marks using the list method sort.
# Developed by: Pragadeeswaran L
# Register No:212223240120
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii) # To find the maximum marks using the list method max().
```Python
# Program to find the maximum marks using the list method max().
# Developed by: Pragadeeswaran L
# Register No: 212223240120
def max_marks(marks):
    large=max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```Python
# Program to find the maximum marks without using builtin functions.
# Developed by: Pragadeeswaran L
# Register No: 212223240120
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
```
## Output:
i) # To find the maximum of marks using the list method sort.
![Screenshot 2024-05-17 232415](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/b5e49a32-8586-43b9-8846-c79d7b1217a0)
![Screenshot 2024-05-17 232427](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/62af2017-77aa-425c-a953-a9236720ad26)
ii) # To find the maximum marks using the list method max().
![Screenshot 2024-05-17 232440](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/5bd61a5e-23f7-459e-95cc-69b251cd350f)
![Screenshot 2024-05-17 232448](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/266444c2-b9dd-4119-8987-5a69f43139e3)
iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-05-17 232501](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/6ed6f348-1047-4daf-aacc-9dc7de1b32a8)
![Screenshot 2024-05-17 232511](https://github.com/Antonyabishek2004/FindMaximum/assets/138849620/3e466e91-ad8a-49bb-8cc1-43efedb9e0bd)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
