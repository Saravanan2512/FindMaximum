# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: G.SARAVANAN
RegisterNumber: 23005445
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
'''
```Python
Program to the maximum marks without using builtin functions.
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
def max_marks(list1):
    # write your code here
    large=max(list1)
    return large



```

## Output:
![image](https://github.com/Saravanan2512/FindMaximum/assets/144979117/36192ba0-a82d-42c1-bbb0-642b215745e7)

![image](https://github.com/Saravanan2512/FindMaximum/assets/144979117/ec92aa26-d4dd-4215-9527-0f02c3d30e66)

![image](https://github.com/Saravanan2512/FindMaximum/assets/144979117/15313acc-f49a-4d93-96f8-e57817e5e0fe)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
